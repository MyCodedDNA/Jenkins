pipeline 
{
    agent any
    tools
    {
        maven  '3.8.4'
    }
    environment 
    {
        JAVA_HOME = 'C:/Program Files/Java/jdk1.8.0_321'
    }
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Building..'
            }
        }
        stage('maven_build')
        {
            steps
            {
                bat 'mvn clean install -Pbump-patch'
            }
        }
    }
    
}

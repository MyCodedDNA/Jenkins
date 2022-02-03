pipeline 
{
    agent any
    tools
    {
        maven  '3.8.4'
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
                bat 'mvn install'
            }
        }
    }
}

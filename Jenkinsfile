pipeline{
    agent any

    stages{

        stage('Build'){
            steps{
                echo 'Building project'             
                bat 'python jenkins_test/hello_world.py'
            }
        }
        stage('Test'){
            steps{
            echo 'Test Stage'
            
            }
        }
    }
}

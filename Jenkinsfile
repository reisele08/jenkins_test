pipeline{
    agent any

    stages{

        stage('Build'){
            steps{
                echo 'Building project'
                g++ "jenkins_test/hello_world.cpp" -o "jenkins_test/hello_world"
            }
        }
        stage('Test'){
            steps{
            echo 'Test Stage'
            
            }
        }
    }
}

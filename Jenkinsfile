pipeline{
    agent any

    stages{

        stage('Build'){
            steps{
                echo 'Building project'
                sh 'g++ -o jenkins_test/hello_world hello_world.cpp'
            }
        }
        stage('Test'){
            steps{
            echo 'Test Stage'
            
            }
        }
    }
}

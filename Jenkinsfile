pipeline{
    agent any

    stages{

        stage('Build'){
            steps{
                echo 'Building project'
                sh 'g++ -o hello_world hello_world.cpp'
            }
        }
        stage('Test'){
            steps{
            echo 'Running project'
            sh './hello_world'
            }
        }
    }
}
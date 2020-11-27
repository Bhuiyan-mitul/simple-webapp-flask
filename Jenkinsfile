pipeline {
    agent any

    stages {
        stage('Build docker image') {
            steps {
                echo "hi this is build"
            }
        }
        stage('Run the image'){
            steps{
                echo "hi this is run"
            }
        }
        stage('the image'){
            steps{
                sh "sudo docker run hello-world"
            }
        }
        
        
    }
}
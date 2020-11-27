pipeline {
    agent any

    stages {
        stage('Build docker image') {
            steps {
                sh "sudo docker build . -t test-web"
            }
        }
        stage('Run the image'){
            steps{
                sh "sudo docker run -d test-web"
            }
        }
        
        
        
    }
}
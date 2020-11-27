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
        stage('kubernetes'){
            steps{
                sh "sudo microk8s kubectl create deployment testweb --image=test-web"
            }
        }
        
        
        
    }
}
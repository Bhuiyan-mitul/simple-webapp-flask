pipeline {
    agent any

    stages {
        stage('Build docker image') {
            steps {
                sh 'docker build . -t test-web-again'
            }
        }
        stage('Run the image'){
            steps{
                sh 'docker run test-web-again'
            }
        }
        
    }
}
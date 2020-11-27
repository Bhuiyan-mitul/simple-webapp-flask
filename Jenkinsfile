pipeline {
    agent {docker {image 'maven:3.3.3'}}

    stages {
        stage('Build docker image') {
            steps {
                sh "mvn --version"
            }
        }
        stage('Run the image'){
            steps{
                echo "hi this is run"
            }
        }
        
    }
}
pipeline {
    agent none
    stages {
        stage('Pipeline from Python') {
            agent {
               docker { image 'python:latest' }
            }
            steps {
                sh 'python --version'
            }
        }
        stage('Pipeline from Groovy') {
            agent {
               docker { image 'groovy:latest' }
            }
            steps {
                sh 'groovy --version'
            }
        }
    }
}

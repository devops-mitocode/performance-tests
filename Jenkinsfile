pipeline {
    agent {
        docker {
            image 'alpine/jmeter:5.6.3'
            args '--entrypoint=""'
        }
    }
    stages {
        stage('Performance Tests') {
            steps {
                sh 'jmeter --version'
            }
        }
    }
}
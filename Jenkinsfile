pipeline {
    agent any

    environment {
        CI = 'true'
    }
    tools {
        nodejs "NodeJS"
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}

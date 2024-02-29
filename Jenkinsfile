pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'RUN apt-get update && apt-get -y install sudo'
                sh 'sudo install npm'
                sh 'npm run build' 
            }
        }
    }
}
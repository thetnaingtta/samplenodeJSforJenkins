pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'apt-get -y install sudo'
                sh 'sudo install npm'
                sh 'npm run build' 
            }
        }
    }
}
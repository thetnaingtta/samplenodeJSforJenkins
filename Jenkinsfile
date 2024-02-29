pipeline {
    agent {label 'agentlinux'} 
    stages {
        stage('Build') { 
            steps {
                sh 'apt-get update && apt-get -y install sudo'
                sh 'sudo install npm'
                sh 'npm run build' 
            }
        }
    }
}
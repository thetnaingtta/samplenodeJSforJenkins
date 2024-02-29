pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'sudo npm install'
                sh 'npm run build' 
            }
        }
    }
}
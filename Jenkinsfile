pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'apt install npm'
                sh 'npm run build' 
            }
        }
    }
}
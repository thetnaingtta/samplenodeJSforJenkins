pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'sudo apt install npm'
                sh 'npm run build' 
            }
        }
    }
}
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'install npm'
                sh 'npm run build' 
            }
        }
    }
}
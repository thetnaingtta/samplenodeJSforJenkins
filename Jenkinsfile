pipeline {
    agent any

    tools {nodejs "Node.js v18.12.1"}

    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
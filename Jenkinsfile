pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/your/repository.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install' // Or any other build tool command
            }
        }
        stage('Compile') {
            steps {
                // Add compile commands here
            }
        }
    }
}

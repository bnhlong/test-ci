pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Ví dụ: sh 'make build' hoặc mvn, npm, etc.
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Ví dụ: sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Ví dụ: sh 'bash deploy.sh'
            }
        }
    }
}


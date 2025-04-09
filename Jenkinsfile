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
                echo 'Installing dependencies...'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace with your actual test command
                sh 'echo "No tests defined"'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker image...'
                sh 'docker build -t my-node-app-1 .'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Running Docker container...'
                sh 'docker run -d -p 3000:3000 --name my-running-app my-node-app-1'
            }
        }
    }
}

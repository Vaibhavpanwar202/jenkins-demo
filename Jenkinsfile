pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/yourusername/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build command
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add deploy commands
            }
        }
    }
}

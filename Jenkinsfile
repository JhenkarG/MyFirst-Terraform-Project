pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/JhenkarG/MyFirst-jenkins-Project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add a test command here if needed
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}

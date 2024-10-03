pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Make sure you are checking out the main branch
                git branch: 'main', url: 'https://github.com/enamouchi/devops-pipeline-1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Add build steps here, such as Maven, Gradle, etc.
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deploy steps here
            }
        }
    }
}

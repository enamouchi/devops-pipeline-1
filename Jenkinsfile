pipeline {
    agent any  
    stages {
        stage('Checkout') {
            steps {
                
                git 'https://github.com/enamouchi/devops-pipeline-1.git'
            }
        }

        stage('Show Date') {
            steps {
              
                script {
                    echo "Current Date: ${new Date()}"
                }
            }
        }
    }
}


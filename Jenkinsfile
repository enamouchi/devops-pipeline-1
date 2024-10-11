pipeline {
    agent any

    tools {
        jdk 'JAVA-HOME'
        maven 'M2-HOME'
    }

    stages {
        stage('GIT') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/enamouchi/devops-pipeline-1.git'
            }
        }

        stage('Compile Stage') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}

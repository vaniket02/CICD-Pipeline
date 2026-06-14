pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/vaniket02/CICD-Pipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Stage Executed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test Stage Executed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy Stage Executed'
            }
        }
    }
}

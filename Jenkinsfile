pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Build started'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Test started'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy started'
            }
        }
    }

    post {
        success {
            echo 'CI/CD Pipeline completed successfully!'
        }

        failure {
            echo 'CI/CD Pipeline failed!'
        }
    }
}

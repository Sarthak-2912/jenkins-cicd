pipeline {
    agent any
    stages {
        stage('Checkout SCM') {
            steps {
                echo 'Source code checkout configured.'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
    post {
        always {
            echo 'CI/CD Pipeline completed successfully!'
        }
    }
}

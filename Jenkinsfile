
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Pipeline loaded from Git SCM'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed successfully'
            }
        }
    }

    post {
        success {
            echo 'All pipeline stages completed successfully!'
        }
    }
}

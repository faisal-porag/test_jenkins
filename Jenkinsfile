pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage!'
            }
        }

        stage('Test') {
            steps {
                 echo 'Test stage!'
            }
        }

        stage('Deploy') {
            steps {
                 echo 'Deploy stage!'
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Cleanup stage!'
            }
        }
    }

    post {
        success {
            // Send notifications or trigger additional jobs on success
            echo 'Build successful!'
        }

        failure {
            // Send notifications or trigger additional jobs on failure
            echo 'Build failed!'
        }
    }
}

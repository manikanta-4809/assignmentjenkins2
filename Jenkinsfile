pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'sleep 5'// Simulate build time
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'sleep 3'// Simulate test time
            }
        }
        stage('Clean up') {
            steps {
                echo 'cleaning up...'
                sh 'sleep 1'// Simulate clean up
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'sleep 2'// Simulate deployment
            }
        }
    }
    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline execution failed!'
        }
    }
}
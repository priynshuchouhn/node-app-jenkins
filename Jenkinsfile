pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo "Building the project..."'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Running tests..."'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                sh 'echo "Deploying the project..."'
            }
        }
    }

    post {
        always {
            echo 'Cleaning up after pipeline run...'
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check the logs.'
        }
    }
}

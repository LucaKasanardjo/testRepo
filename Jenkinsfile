pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building your application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying your application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Send notifications or perform additional tasks here.'
        }
        failure {
            echo 'Pipeline failed! Send notifications or perform cleanup tasks here.'
        }
    }
}

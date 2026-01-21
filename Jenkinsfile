pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Training AI model'
            }
        }

        stage('Test') {
            steps {
                echo 'Validating model accuracy'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying model'
            }
        }

    }

    post {
        success {
            echo 'Pipeline finished successfully'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}

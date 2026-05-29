pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checked Out Changed'
            }
        }
        stage('Build') {
            steps {
                echo 'Build Changed'
            }
        }
        stage('Test') {
            steps {
                echo 'TESTING Changed'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment Changed'
            }
        }
    }
}

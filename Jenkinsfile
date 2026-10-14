pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code pulled from GitHub'
                bat 'dir'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Pipeline loaded from GitHub!'
            }
        }

        stage('Check Source Code') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'cat app.py'
            }
        }
    }
}
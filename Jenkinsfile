pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -ltr'
            }
        }
     stage('Deploy') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}

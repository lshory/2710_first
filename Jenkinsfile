pipeline {
    agent any

    stages {
        stage('build') {
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

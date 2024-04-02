pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
        stage('test') {
            steps {
                echo 'Testing Run stage!'
                sh 'whoami'
                sh 'pwd'
                sh 'ls -al'
            }
        }
    }
}
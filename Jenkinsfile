pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo "Clarusway to reinvent yourself!"
                sh'''
                python3 --version
                python3 pipeline.py
                echo 'that`s all she wrote!'
                '''
            }
        }
    }
}
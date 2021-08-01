pipeline {
    agent {
        label 'master'
    }

    stages {
        stage('Execute') {
            steps {
                sh '''
                ls
                python app.py
                sleep 1m
                '''
            }
        }
    }
}

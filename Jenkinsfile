pipeline {
    agent {
        label 'master'
    }

        stage('Execute') {
            steps {
                sh '''
                ls
                python app.py
                '''
            }
        }
    }
}

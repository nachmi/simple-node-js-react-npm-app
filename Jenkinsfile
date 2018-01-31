pipeline {
    agent none
    stages {
        stage('Build') {
            steps {
                sh 'mkdir /.nmp'
                sh 'chmod -R 777 /.npm'
                sh 'npm install'
            }
        }
    }
}

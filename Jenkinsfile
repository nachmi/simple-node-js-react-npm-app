pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
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

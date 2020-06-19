pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                bat 'go version'
            }
        }
    }
}
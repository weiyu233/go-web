// Run on an agent where we want to use Go
pipeline {
    agent { docker { image 'golang:1.17.5-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
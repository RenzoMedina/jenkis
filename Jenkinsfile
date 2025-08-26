pipeline {
    agent { docker { image 'golang:1.25.0-alpine3.22' } }
    stages {
        stage('Docker Check') {
            steps {
               sh 'docker version'
            }
        }
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
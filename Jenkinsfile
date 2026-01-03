/* Requires the Docker Pipeline plugin , test pr*/
pipeline {
    agent { dockerContainer { image 'node:24.12.0-alpine3.23' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}

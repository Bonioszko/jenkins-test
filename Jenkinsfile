/* Requires the Docker Pipeline plugin , test pr*/
pipeline {
    agent { 
        docker { 
            image 'node:24.12.0-alpine3.23'
            args '-v /var/jenkins_home/workspace:/workspace'
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
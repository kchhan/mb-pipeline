pipeline {
    agent any

    environment {
        BRANCH = 'dev'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building ${env.BUILD_ID}:${env.BUILD_NUMBER} on branch ${env.BRANCH}'
            }
        }
    }
}
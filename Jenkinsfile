pipeline {
    agent any

    environment {
        BRANCH = 'master'
    }

    stages {
        stage('Build') {
            steps {
                echo "Building ${env.BUILD_ID}:${env.BUILD_NUMBER} on branch ${BRANCH}" >> file.txt
            }
        }
    }
}
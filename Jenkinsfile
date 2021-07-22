pipeline {
    agent any

    environment {
        BRANCH = 'master'
    }

    stages {
        stage('Build') {
            steps {
                echo "Building ${env.BUILD_ID}:${env.BUILD_NUMBER} on branch ${env.BRANCH}" >> file.txt
            }
        }
    }
}
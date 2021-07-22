pipeline {
    agent any

    environment {
        BRANCH = 'master'
    }

    stages {
        stage('Build') {
            steps {
                writeFile file: "file-${BRANCH}-${BUILD_NUBMER}.txt", text: "${JOB_NAME} : ${BUILD_NUMBER}"
            }
        }
    }
}
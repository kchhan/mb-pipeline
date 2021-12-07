pipeline {
    agent any

    environment {
        BRANCH = 'dev'
    }

    stages {
        stage('Build') {
            steps {
                writeFile file: "file-${BRANCH}-${BUILD_NUMBER}.txt", text: "${JOB_NAME} : ${BUILD_NUMBER}"
            }
        }
    }
}

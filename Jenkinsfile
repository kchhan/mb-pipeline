pipeline {
    agent any

    options {
        durabilityHint('PERFORMANCE_OPTIMIZED') 
    }

    environment {
        BRANCH = 'durability'
    }

    stages {
        stage('Build') {
            steps {
                writeFile file: "file-${BRANCH}-${BUILD_NUMBER}.txt", text: "${JOB_NAME} : ${BUILD_NUMBER}"
            }
        }
    }
}
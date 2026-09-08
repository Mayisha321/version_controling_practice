pipeline {
    agent { label 'cicd' }

    environment {
        BLEH = 'Hello'
    }

    stages {
        stage('Test') {
            steps {
                echo "${BLEH}"
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Dump Env') {
            steps {
                echo sh(script: 'env|sort', returnStdout: true)
            }
        }
        stage('Webhook Payload') {
            echo "Payload: ${env.payload}"
        }
    }
}

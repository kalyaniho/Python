
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from Jenkins Pipeline!'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished.'
        }
    }
}

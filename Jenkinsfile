pipeline {
    agent {
        node {
            label "linux"
        }
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }

    post {
        always {
            echo "Always"
        }
        success {
            echo "Success"
        }
        failure {
            echo "Failure"
        }
        cleanup {
            echo "Cleanup"
        }
    }
}

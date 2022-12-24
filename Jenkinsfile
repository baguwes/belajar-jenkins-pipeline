pipeline {
    agent {
        node {
            label "linux"
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
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

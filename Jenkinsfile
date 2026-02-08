pipeline {
    agent any

    options {
        disableConcurrentBuilds()
        timestamps()
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checkout ho raha hai'
            }
        }

        stage('Verify Jenkinsfile') {
            steps {
                echo 'Jenkinsfile mil gaya, sab theek hai!'
            }
        }

        stage('Docker Check') {
            steps {
                sh 'docker version'
            }
        }

        stage('Build') {
            steps {
                echo 'Application build ho rahi hai'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests run ho rahe hain'
            }
        }

        stage('Integration Test') {
            steps {
                echo 'Integration tests run ho rahe hain'
            }
        }
    }

    post {
        always {
            echo 'Pipeline complete hui (success ya failure)'
        }
        success {
            echo 'Pipeline SUCCESSFUL 🎉'
        }
        failure {
            echo 'Pipeline FAILED ❌'
        }
    }
}

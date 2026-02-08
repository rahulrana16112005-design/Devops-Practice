pipeline {
    agent any

    stages {
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
    }
}

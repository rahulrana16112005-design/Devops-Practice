pipeline {
  agent {
    docker {
      image 'jenkins/jenkins:lts'
    }
  }
  stages {
    stage('Check') {
      steps {
        sh 'docker --version'
      }
    }
  }
}


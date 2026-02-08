pipeline {
  agent {
    docker {
      image 'docker:latest'
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


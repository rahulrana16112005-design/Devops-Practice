pipeline {
  agent {
    docker {
      image 'docker:24-cli'
      args '-v /var/run/docker.sock:/var/run/docker.sock'
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


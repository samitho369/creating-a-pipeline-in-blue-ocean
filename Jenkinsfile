pipeline {
  agent {
    docker {
      image 'node:22-alpine'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'npm install'
      }
    }

  }
}
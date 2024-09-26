pipeline {
  agent {
    docker {
      image 'node:16-alpine'
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
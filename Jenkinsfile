pipeline {
  agent {
    docker {
      args '-p 3000:9008'
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image '192.168.104.241/common/node:6-alpine'
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
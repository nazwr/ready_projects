pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'ubuntu:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install -g testengine-cli'
        sh '''apt-get install
apt-get install node-js
apt-get update
'''
        sh 'ls'
      }
    }

  }
}
pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
      args '-u root'
    }
  }
  stages{
    stage('Build'){
      steps {
        sh 'npm install'
      }
    }
  }
}

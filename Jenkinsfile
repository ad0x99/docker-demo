pipeline {
  agent {
    node {
      label 'builder'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}
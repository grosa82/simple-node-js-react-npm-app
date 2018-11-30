pipeline {
  agent {
    node {
      label 'Agent'
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
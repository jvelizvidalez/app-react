pipeline {
  agent {
    node {
      label 'Built-In Node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'yarn install'
        sh 'yarn build'
      }
    }

  }
}
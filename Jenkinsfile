pipeline {
  agent {
    node {
      label 'NodeJS'
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
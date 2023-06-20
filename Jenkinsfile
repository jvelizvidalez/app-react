pipeline {
  agent {
    node {
      label 'NodeJS'
    }

  }
  tools {
    nodejs 'nodejs'
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

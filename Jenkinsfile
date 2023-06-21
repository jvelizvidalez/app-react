pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        node {
          label 'NodeJS'
        }

      }
      steps {
        sh 'yarn install'
        sh 'yarn build'
      }
    }

  }
}
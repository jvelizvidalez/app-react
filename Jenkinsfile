pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        nodejs('nodejs') {
          sh 'yarn install'
          sh 'yarn build'
        }

      }
    }

  }
}
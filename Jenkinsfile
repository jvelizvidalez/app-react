pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        nodejs('NodeJS') {
          sh 'yarn install'
          sh 'yarn build'
        }
      }
    }
  }
}

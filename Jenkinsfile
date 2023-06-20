pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'yarn install'
        powershell 'yarn build'
      }
    }

  }
}
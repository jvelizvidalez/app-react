pipeline {
  agent any
  stages {
    stage('asdas') {
      agent {
        node {
          label 'NodeJSInstallation'
        }

      }
      steps {
        node(label: 'NodeJS') {
          sh 'yarn  install'
        }

      }
    }

  }
}
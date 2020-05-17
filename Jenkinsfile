pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ansible linux -m ping'
      }
    }

  }
}
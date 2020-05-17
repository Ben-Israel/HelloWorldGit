pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
ansible linux -m ping -u jenkins --become-user benny'''
      }
    }

  }
}
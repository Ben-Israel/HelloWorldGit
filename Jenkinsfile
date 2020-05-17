pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
ls -alh
ansible linux -m ping -u benny --become'''
      }
    }

  }
}
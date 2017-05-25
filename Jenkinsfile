pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh '''apk update
'''
        sh 'apk upgrade'
      }
    }
    stage('done') {
      steps {
        echo 'bla'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh 'apk update'
      }
    }
    stage('done') {
      steps {
        echo 'bla'
      }
    }
  }
  environment {
    PATH = '/bin/sh'
  }
}
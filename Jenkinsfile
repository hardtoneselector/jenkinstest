pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh '''apk update
apk upgrade'''
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
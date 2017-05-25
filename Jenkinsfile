pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        isUnix()
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
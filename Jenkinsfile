pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh 'echo $UUID'
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
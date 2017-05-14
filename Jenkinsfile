pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh 'apk --update add --no-cache mercurial git'
      }
    }
    stage('done') {
      steps {
        echo 'bla'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh 'apk --update add --no-cache mercurial git'
        sh 'apk --update add --no-cache docker'
      }
    }
    stage('done') {
      steps {
        echo 'bla'
      }
    }
  }
}
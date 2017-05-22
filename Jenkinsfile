pipeline {
  agent {
    node {
      label 'odroid'
    }
    
  }
  stages {
    stage('init') {
      steps {
        echo 'init'
        sh 'apk --upgrade'
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
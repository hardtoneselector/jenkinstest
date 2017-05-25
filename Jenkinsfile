pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'init'
        isUnix()
        git(url: 'https://github.com/zikula/core.git', branch: '1.5', changelog: true, poll: true, credentialsId: 'hardtoneselector')
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
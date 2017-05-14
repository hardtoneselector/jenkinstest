pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        parallel(
          "init": {
            echo 'JENKINS: INIT'
            sleep 5
            echo 'INIT: ENDE'
            sleep 5
            
          },
          "test": {
            sleep 5
            
          },
          "": {
            echo 'tghz'
            
          }
        )
      }
    }
    stage('done') {
      steps {
        echo 'bla'
      }
    }
  }
}
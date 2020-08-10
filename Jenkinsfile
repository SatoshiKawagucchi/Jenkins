pipeline {
  agent any
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            sh 'echo \'start\''
          }
        }

        stage('start2') {
          steps {
            sleep 5
          }
        }

      }
    }

  }
}
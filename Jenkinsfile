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

    stage('start3') {
      steps {
        timestamps() {
          sleep 5
        }

      }
    }

    stage('end') {
      steps {
        echo 'End!'
      }
    }

  }
}
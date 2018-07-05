pipeline {
  agent any
  stages {
    stage('No.1') {
      steps {
        sleep 10
      }
    }
    stage('No.2') {
      parallel {
        stage('No.2') {
          steps {
            echo 'ss'
          }
        }
        stage('No.3') {
          steps {
            sh 'ff'
          }
        }
        stage('No.4') {
          steps {
            sh 'gg'
          }
        }
      }
    }
  }
}
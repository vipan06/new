pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('test') {
      steps {
        echo 'testing....'
      }
    }

    stage('Deploy') {
      steps {
        sleep 10
      }
    }

  }
}
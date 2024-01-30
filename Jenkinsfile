pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd 
date'''
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Hello How Are You?'
          }
        }

        stage('Testing Parallel') {
          steps {
            echo 'data'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploymnt'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo'
      }
    }
    stage('Backend') {
      parallel {
        stage('Unit') {
          steps {
            sh 'echo Backend'
            sh 'echo Unit'
          }
        }
        stage('Performance') {
          steps {
            sh 'echo Performance'
          }
        }
      }
    }
    stage('Frontend') {
      steps {
        sh 'echo Frontend'
      }
    }
    stage('Static Analysis') {
      steps {
        sh 'echo static'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploy'
      }
    }
  }
}
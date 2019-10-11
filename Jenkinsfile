pipeline {
  agent {
    docker {
      image 'maven:3.6.2-jdk-8'
      args 'C:\\Program Files\\maven3.6.2\\bin'
    }

  }
  stages {
    stage('Compile') {
      steps {
        ws(dir: 'C:\\Program Files\\Git\\usr\\bin') {
          sh 'echo build'
        }

      }
    }
  }
}
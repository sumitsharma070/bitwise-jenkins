pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'git \'https://github.com/sumitsharma070/jhipster-sample-app', branch: 'master')
        bat 'mvnHome = tool \'M3\''
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'git \'https://github.com/sumitsharma070/jhipster-sample-app', branch: 'master', credentialsId: '188ce79b-de69-480b-a8b5-c3a72c827761')
        bat 'mvnHome = tool \'M3\''
      }
    }
  }
}
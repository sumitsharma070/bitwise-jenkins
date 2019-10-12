pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'https://github.com/sumitsharma070/jhipster-sample-app.git', branch: 'master', credentialsId: '188ce79b-de69-480b-a8b5-c3a72c827761')
        bat 'def mvnHome = tool \'M3\''
      }
    }
  }
}
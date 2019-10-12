pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'https://github.com/sumitsharma070/jhipster-sample-app.git', branch: 'master', credentialsId: 'e2d94792-6bd6-4bda-84bd-ac1bf3c7a845')
      }
    }
  }
}
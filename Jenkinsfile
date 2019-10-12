pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        git(url: 'https://github.com/sumitsharma070/jhipster-sample-app.git', branch: 'master', credentialsId: 'e2d94792-6bd6-4bda-84bd-ac1bf3c7a845')
        node(label: 'compile') {
          bat(script: 'def mvnHome = tool \'M3\'', returnStatus: true)
        }

      }
    }
    stage('Build') {
      steps {
        dir(path: 'MAVEN_HOME=$mvnHome') {
          bat(script: 'bat(/"%MAVEN_HOME%\\bin\\mvn" -Dmaven.test.failure.ignore clean package/)', returnStatus: true)
        }

        bat(script: 'bat(/"%MAVEN_HOME%\\bin\\mvn" -Dmaven.test.failure.ignore clean package/)', returnStatus: true)
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'bat(/"%MAVEN_HOME%\\bin\\mvn" -Dmaven.test.failure.ignore clean package/)'
      }
    }
  }
}
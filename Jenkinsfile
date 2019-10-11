pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ws(dir: 'C:\\Program Files\\Git\\usr\\bin\\bash.exe') {
          sh '''pipeline{
   agent any
   stages {
     stage(\'Build\'){
        steps{
            sh \'mvn\'
             }
           }
       }
  }'''
          }

        }
      }
    }
  }
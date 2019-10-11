pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ws(dir: 'C:\\Program Files\\Git\\usr\\bin') {
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
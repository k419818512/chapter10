pipeline {
   agent any;
   stages {
      stage('Preparing the environment') {
         steps {
            sh 'Preparing the enviornment'
            }
         }  
      stage('Code Quality') {
         steps {
            sh 'echo checking the code quality'
         }
      }
      stage('Tests') {
         steps {
            sh 'echo perfoming the tests'
         }
      }
      stage('Build') {
         steps {
            sh 'exit 1'
         }
      }
      stage('Delivery') {
         steps {
            sh 'exit 1'
         }
      }
      stage('Deploy') {
         steps {
            sh 'exit 1'
         }
      }     
   }
}
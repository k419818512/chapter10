pipeline {
   agent any;
   stages {
      stage('Preparing the environment') {
         steps {
            sh 'echo Preparing the enviornment'
            sh 'apt-get clean'
            sh 'python3 -m pip install requirements.txt'
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
            sh 'echo preparing Build'
         }
      }
      stage('Delivery') {
         steps {
            sh 'echo Preparing delivery'
         }
      }
      stage('Deploy') {
         steps {
            sh 'echo preparing deploy'
         }
      }     
   }
}
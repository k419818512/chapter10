pipeline {
   agent any;
   stages {
      stage('Preparing the environment') {
         steps {
            sh 'echo Preparing the enviornment'
            sh 'apt-get clean'
            sh 'python3 -m pip install -r requirements.txt --break-system-packages'
            }
         }  
      stage('Code Quality') {
         steps {
            sh 'echo checking the code quality'
            sh 'python3 -m pylint app.py --disable=C0114 --disable=C0116 --disable=W0311'
         }
      }
      stage('Tests') {
         steps {
            sh 'echo perfoming the tests'
            sh 'python3 -m pytest'
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
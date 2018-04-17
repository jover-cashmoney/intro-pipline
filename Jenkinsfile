library 'SharedLibs'
pipeline {
  agent any
  stages {
     stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
     }  
   }
  environment {
    MY_NAME = 'Mary'
    TEST_USER = credentials('test-user')
  }
  post {
    aborted {
      echo 'Why didn\'t you push my button?  
    }
}

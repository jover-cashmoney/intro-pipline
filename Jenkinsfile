pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
    }
    
  }
  stages {
    stage('hello world') {
      steps {
        echo 'hello world'
        sh 'go version'
      }
    }
  }
}
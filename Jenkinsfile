pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello world!'
        sh 'java -version'
      }
    }
  }
}
pipeline {
  agent none
  stages {
    stage('Build & Test') {
      agent any
      steps {
        sh 'mvn -Dmaven.test.failure.ignore clean package'
      }
    }

  }
}
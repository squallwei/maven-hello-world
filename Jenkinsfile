pipeline {
  agent none
  stages {
    stage('Build & Test') {
      agent any
      steps {
        sh '''cd maven-hello-world_master
mvn -Dmaven.test.failure.ignore clean package'''
      }
    }

  }
}
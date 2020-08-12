pipeline {
  agent none
  stages {
    stage('Build & Test') {
      agent any
      steps {
        sh '''pwd
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false'''
      }
    }

  }
}
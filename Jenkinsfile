pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh \'mvn -B -DskipTests clean package\''
      }
    }
  }
}
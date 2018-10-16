pipeline {
  agent any
    tools {
        maven 'Maven 3.5.4'
        jdk 'jdk8'
    }
  stages {
    stage('Build') {
      steps {
        sh './mvn -B clean package'
      }
    }
  }
}
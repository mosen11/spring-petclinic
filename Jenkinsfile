pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git 'git@github.com:mosen11/spring-petclinic.git'
      }
    }
    stage('build') {
      steps {
        build 'clean install'
        build 'mvn clean install'
      }
    }
  }
}
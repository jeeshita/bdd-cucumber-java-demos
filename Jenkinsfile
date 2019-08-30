pipeline {
  agent any
  stages {
    stage('GetCode') {
      steps {
        git(url: 'https://github.com/jeeshita/bdd-cucumber-java-demos.git', branch: 'master')
      }
    }
  }
}
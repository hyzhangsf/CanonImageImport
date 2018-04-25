pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'nosetests tests/'
      }
    }
  }
}
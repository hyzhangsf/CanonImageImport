pipeline {
  agent none
  stages {
    stage('test python') {

      steps {
        sh 'python tests/test_handler.py'
      }
    }
  }
}

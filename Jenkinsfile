pipeline {
  agent any
  stages {
    stage('test python') {
      steps {
        sh '''echo "Hello World"
python tests/test_handler.py'''
      }
    }
  }
}
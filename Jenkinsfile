pipeline {
  agent none
  stages {
    stage('test python') {
      agent {
        docker {
          image 'ubuntu:latest'
        }

      }
      steps {
        sh 'python tests/test_handler.py'
      }
    }
  }
}
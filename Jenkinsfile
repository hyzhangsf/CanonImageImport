pipeline {
  agent {
    docker {
      image 'ubuntu:latest'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'nosetests tests/'
      }
    }
  }
}
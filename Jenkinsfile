pipeline {
  agent {
    docker {
      image 'ubuntu:14.04'
    }

  }
  stages {
    stage('test python') {
      steps {
        sh '''apt-get install python mvn
mvn --version'''
      }
    }
  }
}
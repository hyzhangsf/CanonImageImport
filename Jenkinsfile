pipeline {
  agent {
    docker {
      image 'ubuntu:14.04'
    }

  }
  stages {
    stage('test python') {
      steps {
        sh '''mvn --version
sudo apt-get install python'''
      }
    }
  }
}
pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
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
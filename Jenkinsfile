pipeline {
  agent {
    docker {
      image 'ubuntu:14.04'
    }

  }
  stages {
    stage('test python') {
      steps {
        sh 'sudo apt-get install python mvn'
      }
    }
  }
}
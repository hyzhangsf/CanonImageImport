pipeline {
  agent {
    docker {
      image 'ubuntu:latest'
    }

  }
  stages {
    stage('test python') {
      agent {
        docker {
          image 'ubuntu:latest'
        }

      }
      steps {
        sh 'nosetests tests/'
      }
    }
  }
}
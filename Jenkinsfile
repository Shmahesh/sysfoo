pipeline {
  agent {
    docker {
      image 'maven:3.6.3-jdk-11-slim'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'step build'
      }
    }

    stage('test') {
      steps {
        echo 'step test'
      }
    }

    stage('package') {
      steps {
        echo 'step package'
        echo 'Passed'
      }
    }

  }
}
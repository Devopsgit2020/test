pipeline {
  agent {
    docker {
      image 'node:18.17.1-alpine3.18'
    }

  }
  stages {
    stage('Fluffy Build') {
      steps {
        sh 'echo Another Placeholder'
      }
    }

    stage('Fluffy Test') {
      steps {
        sh 'sleep 5'
        sh 'echo Success!'
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'Placeholder'
      }
    }

  }
}
pipeline {
  agent {
    node {
      label 'testcloud'
    }

  }
  stages {
    stage('Fluffy Build') {
      agent {
        docker {
          image 'centos'
        }

      }
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
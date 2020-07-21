pipeline {
  agent {
    docker { image 'docker:dind'}
  }
  stages {
    stage('build') {
      steps {
        echo 'Beginning Build'
        sh 'docker build .'
      }
    }

  }
}

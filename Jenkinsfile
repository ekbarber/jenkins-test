pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Beginning Build ${GIT_COMMIT}'
        sh 'docker build .'
      }
    }

  }
}

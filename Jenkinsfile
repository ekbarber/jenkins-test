pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Beginning Build'
        sh 'docker build .'
      }
    }
  }
}

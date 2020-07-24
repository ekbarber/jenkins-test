pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "Beginning Build ${GIT_COMMIT}"

        docker.build('755448414176.dkr.ecr.us-east-1.amazonaws.com/jenkins-test')
      }
    }
  }
}

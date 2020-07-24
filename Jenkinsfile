pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "Beginning Build ${GIT_COMMIT}"
        script{
          def img = docker.build '755448414176.dkr.ecr.us-east-1.amazonaws.com/jenkins-test:${env.BUILD_ID}'
          img.push()
        }

      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('echo branch') {
      steps {
        sh 'printenv'
        echo '"The build number is ${env.BUILD_NUMBER}"'
        sh 'echo "I can access $BUILD_NUMBER in shell command as well."'
      }
    }

  }
}
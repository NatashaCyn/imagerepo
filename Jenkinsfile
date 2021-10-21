pipeline {
  agent any
  stages {
    stage('echo branch') {
      steps {
        sh 'printenv'
        echo '"The build number is ${BRANCH_NAME}"'
        sh 'echo "I can access $BRANCH_NAME in shell command as well."'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('echo branch') {
      steps {
        sh 'printenv'
        echo '${env.BRANCH_NAME}'
      }
    }

  }
}
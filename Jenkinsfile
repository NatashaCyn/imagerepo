pipeline {
  agent any
  stages {
    stage('echo branch') {
      steps {
        sh 'printenv'
        echo '\'Pulling...\' + env.BRANCH_NAME'
      }
    }

  }
}
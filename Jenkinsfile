pipeline {
  agent any
  stages {
    stage('echo branch') {
      steps {
        sh '''Pulling... ${env.GIT_BRANCH}
'''
        sh 'printenv'
      }
    }

  }
}
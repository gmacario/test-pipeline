pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'printenv | sort'
      }
    }
  }
  environment {
    EXORBSP_BRANCH = "${env.BRANCH_NAME}"
  }
}

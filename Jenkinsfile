pipeline {
  agent any
  stages {
    stage('development-branch') {
      when{
        branch 'development'
      }
      steps {
        echo 'run this stage - ony if the branch = development branch'
         sh 'echo Building ${BRANCH_NAME}...'
      }
    }
    stage('master-branch') {
      when{
        branch 'master'
      }
      steps {
        echo 'run this stage - ony if the branch = master branch'
         sh 'echo Building ${BRANCH_NAME}...'
      }
    }
  }
}

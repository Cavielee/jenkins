pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hello world'
      }
    }

    stage('stage2') {
      steps {
        echo env.BRANCH_NAME
      }
    }
  }
}
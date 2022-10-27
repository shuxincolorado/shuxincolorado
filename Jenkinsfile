pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "This is a pipeline test of $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
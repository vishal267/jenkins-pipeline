pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    demo = '1'
  }
}
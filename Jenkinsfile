pipeline {
  agent {
    node {
      label 'node_lbl'
    }

  }
  stages {
    stage('Test') {
      steps {
        echo 'Hi Skully'
      }
    }
  }
  environment {
    NODE_ENV = 'test'
  }
}
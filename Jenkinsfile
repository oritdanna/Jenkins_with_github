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
        bat(script: 'react-scripts start', encoding: 'UTF8', returnStatus: true)
      }
    }
  }
  environment {
    NODE_ENV = 'test'
  }
}
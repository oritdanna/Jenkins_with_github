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
        sh 'npm run test'
      }
    }
  }
}
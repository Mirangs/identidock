pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Run Tests') {
      steps {
        sh 'ls -al'
      }
    }

  }
  environment {
    ENV = 'UNIT'
  }
}
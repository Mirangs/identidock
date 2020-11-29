pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Run Tests') {
      steps {
        sh 'python tests.py'
      }
    }

  }
  environment {
    ENV = 'UNIT'
  }
}
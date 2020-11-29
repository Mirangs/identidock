pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Run Tests') {
      steps {
        sh 'python app/tests.py'
      }
    }

  }
  environment {
    ENV = 'UNIT'
  }
}
pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Run image') {
      steps {
        sh 'python --version'
      }
    }

  }
  environment {
    ENV = 'UNIT'
  }
}
pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Run image') {
      steps {
        sh 'docker images'
      }
    }

  }
  environment {
    ENV = 'UNIT'
  }
}
pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        error 'sleep 5'
        sleep 5
      }
    }
  }
  post {
    always {
      echo 'Siempre'

    }

    success {
      echo 'Todo Bien'

    }

    unstable {
      echo 'Inestable'

    }

    failure {
      echo 'Fallo'

    }

  }
}
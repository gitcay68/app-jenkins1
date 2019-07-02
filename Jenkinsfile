pipeline {
  agent any
  stages {
    stage('Mensaje') {
      steps {
        echo 'Hola desde stage1'
      }
    }
    stage('Mensaje2') {
      steps {
        echo 'Hola stage 2'
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
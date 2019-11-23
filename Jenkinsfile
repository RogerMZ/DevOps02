pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        echo 'Iniciando proceso'
        sh 'uname -a'
      }
    }

    stage('Build') {
      steps {
        sh 'gcc --version'
      }
    }

  }
}
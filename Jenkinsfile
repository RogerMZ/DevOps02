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
      parallel {
        stage('Build') {
          steps {
            sh 'gcc --version'
          }
        }

        stage('Build Web') {
          steps {
            sh 'php --version'
          }
        }

      }
    }

  }
}
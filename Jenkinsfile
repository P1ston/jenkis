pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'Hola desde stage inicio'
        sh 'docker build -t app .'
      }
    }

    stage('Paso 2') {
      steps {
        echo 'Hola desde stage 2'
      }
    }
    stage('Paso 3') {
      steps {
        echo 'DEPLOY'
      }
    }

  }
}
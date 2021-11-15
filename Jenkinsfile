pipeline {
  agent any
  stages {
    stage('Git') {
      parallel {
        stage('Git') {
          steps {
            echo 'Git'
          }
        }

        stage('Comprueba') {
          steps {
            echo 'Comprueba'
          }
        }

      }
    }

    stage('Fuente') {
      parallel {
        stage('Fuente') {
          steps {
            echo 'Fuente'
          }
        }

        stage('Espera') {
          steps {
            echo 'Espera'
          }
        }

      }
    }

  }
}
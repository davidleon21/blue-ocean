pipeline {
  agent any
  stages {
    stage('compilar') {
      steps {
        echo 'compilando '
        bat 'Get-Date -Format "dd/MM/yyyy"'
      }
    }

    stage('testing') {
      steps {
        echo 'i\'m testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}
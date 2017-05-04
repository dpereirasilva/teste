pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Bui dando...kkkkk'
      }
    }
    stage('Teste') {
      steps {
        echo 'Testando...'
      }
    }
    stage('Qualidade do Código') {
      steps {
        echo 'Verificando a Qualidade do Codigo....'
      }
    }
    stage('Deploy MGMT') {
      steps {
        echo 'Realizando Deploy'
      }
    }
    stage('Maven') {
      steps {
        sh 'sh \'mvn --version\''
      }
    }
  }
}
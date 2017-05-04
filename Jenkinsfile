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
  }
  post {
    always {
      echo 'This will always run'
      
    }
    
    success {
      echo 'This will run only if successful'
      
    }
    
    failure {
      echo 'This will run only if failed'
      
    }
    
    unstable {
      echo 'This will run only if the run was marked as unstable'
      
    }
    
    changed {
      echo 'This will run only if the state of the Pipeline has changed'
      echo 'For example, if the Pipeline was previously failing but is now successful'
      
    }
    
  }
}
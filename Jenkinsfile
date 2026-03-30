pipeline {
  agent any
    environment {
      SEMGREP_APP_TOKEN = credentials('SEMGREP_APP_TOKEN')
    }
  stages {
    stage('Semgrep-Scan'){
      steps{
        powershell '''semgrep ci '''
      }
    }
  }
}
        
        

pipeline {
  agent any
    environment {
      SEMGREP_APP_TOKEN = credentials('SEMGREP_APP_TOKEN')
    }
  stages {
    stage('Semgrep-Scan'){
      steps{
        powershell '"C:\\Users\\vaibh\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\semgrep.exe" ci'
      }
    }
  }
}
        
        

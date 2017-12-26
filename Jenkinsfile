pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo \'Hello world 111\''
      }
    }
    stage('Call powershall script') {
      steps {
        powershell 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\hello_ps.ps1'
      }
    }
  }
}
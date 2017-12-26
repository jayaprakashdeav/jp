pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo \'Hello world 111\''
      }
    }
    stage('Call Batch File') {
      steps {
        bat 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\Bat_Hello.bat'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'echo \'Hello world 111\''
          }
        }
        stage('Python parallel calling') {
          steps {
            bat 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\Hello_Pyton.bat'
          }
        }
      }
    }
    stage('Call power shall using Batch File') {
      steps {
        bat 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\hello_ps.bat'
      }
    }
    stage('Python') {
      steps {
        bat 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\Hello_Pyton.bat'
      }
    }
  }
}
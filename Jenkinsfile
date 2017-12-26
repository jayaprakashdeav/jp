pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo \'Hello world 111\''
      }
    }
    stage('Call power shall using Batch File') {
      steps {
        bat 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\hello_ps.bat'
      }
    }
    stage('Python') {
      steps {
        bat(script: 'C:\\Users\\jayaprakash.s\\Desktop\\delete\\hello_python.py', encoding: 'python hello_python.py')
      }
    }
  }
}
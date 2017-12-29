pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat(script: 'echo "Yatao"', returnStatus: true)
          }
        }
        stage('Test') {
          steps {
            bat(script: 'echo "Yes, it works."', returnStatus: true)
          }
        }
        stage('StartET') {
          steps {
            bat(script: 'C:\\Users\\Toto\\Documents\\GitHub\\startET.bat', returnStatus: true)
          }
        }
      }
    }
  }
}
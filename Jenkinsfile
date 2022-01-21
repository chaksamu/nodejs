pipeline {
    agent any
  stages{
    stage('Checkout Code'){
      steps {
       git branch: 'main', url: 'https://github.com/chaksamu/nodejs.git'
      }
    }
    stage('Execute the Code'){
       steps {
            sh 'node app.js'
      }
    }
  }
}

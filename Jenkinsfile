pipeline {
    agent any
  stages{
    stage('Checkout Code'){
      steps {
       git https://github.com/chaksamu/nodejs.git
      }
    }
    stage('Execute the Code'){
       steps {
            pwsh 'node app.js'
      }
    }
  }
}

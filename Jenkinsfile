pipeline {
  agent any
  stages {
    stage('Code Checkout') {
      steps {
        git(url: 'https://github.com/hualdajani/myFirstwebApp.git', branch: '*/master', changelog: true, credentialsId: 'hualdajani')
      }
    }

  }
}
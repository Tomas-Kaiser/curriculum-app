pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/Tomas-Kaiser/curriculum-app', branch: 'dev')
      }
    }

    stage('Parallel') {
      steps {
        sh 'ls -la'
      }
    }

  }
}
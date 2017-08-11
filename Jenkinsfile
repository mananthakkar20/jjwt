pipeline {
  agent any
  stages {
    stage('Pull') {
      steps {
        git(url: 'https://github.com/mananthakkar20/jjwt', poll: true, branch: 'master')
      }
    }
  }
}
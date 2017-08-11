pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/mananthakkar20/jjwt', poll: true, branch: 'master')
      }
    }
  }
}
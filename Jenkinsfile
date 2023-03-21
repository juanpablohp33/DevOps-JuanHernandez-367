pipeline {
  agent any
  stages {
    stage('checkout Code') {
      steps {
        git(url: 'https://github.com/juanpablohp33/DevOps-JuanHernandez-367', branch: 'master')
      }
    }

    stage('error') {
      steps {
        sh 'ls -la'
      }
    }

  }
}
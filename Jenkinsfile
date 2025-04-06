pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        git 'https://github.com/shraddhaSshelke/jenkins-ci-cd-pipeline.git'
      }
    }

    stage('Build') {
      steps {
        sh 'echo Building the app...'
      }
    }

    stage('Test') {
      steps {
        sh 'echo Running tests...'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo Deploying the app...'
      }
    }
  }
}

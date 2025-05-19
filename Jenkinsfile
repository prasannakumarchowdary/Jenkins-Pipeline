pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'planning an application'
      }
    }

    stage('code') {
      steps {
        echo 'code required for application'
      }
    }

    stage('build') {
      steps {
        echo 'build the code'
      }
    }

    stage('test') {
      steps {
        echo 'test the code'
      }
    }

    stage('release') {
      steps {
        echo 'test code should be moved to release'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying the application'
      }
    }

    stage('operate') {
      steps {
        echo 'operating the application'
      }
    }

  }
}
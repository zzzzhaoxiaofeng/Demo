pipeline {
  agent {
    node {
      label 'demo'
    }

  }
  stages {
    stage('Git pull') {
      steps {
        git 'https://github.com/zzzzhaoxiaofeng/Demo.git'
      }
    }

    stage('Build') {
      steps {
        bat 'python 1.py'
      }
    }

  }
}
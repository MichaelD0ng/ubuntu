pipeline {
  agent any
  stages {
    stage('Build Docker') {
      steps {
        echo 'Docker building...'
      }
    }
    stage('Docker Images') {
      steps {
        sh 'docker build -t docker.io/ubuntu:pipelines -f base/Dockerfile .'
      }
    }
  }
}
pipeline {
  agent {
    docker {
      image 'maven:3.5.0-jdk-8'
      args '-v /root/.m2:/root/.m2'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}
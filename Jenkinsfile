pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
      }
    }
    stage('Shell Script') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}
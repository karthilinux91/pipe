pipeline {
  agent any
  stages {
    stage('SQA-Blink-01') {
      steps {
        build 'SQA-Blink-01'
        build 'SQA-InjectError-02'
      }
    }
    stage('SQA-InjectError-02') {
      steps {
        build 'SQA-InjectError-02'
      }
    }
  }
}
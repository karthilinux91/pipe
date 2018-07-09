pipeline {
  agent any
  stages {
    stage('SQA-Blink-01') {
      steps {
        build(job: 'SQA-Blink-01', propagate: false)
      }
    }
    stage('SQA-InjectError-02') {
      steps {
        build(job: 'SQA-InjectError-02', propagate: false)
      }
    }
  }
}

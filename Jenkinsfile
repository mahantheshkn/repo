pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sleep 5
      }
    }

    stage('Build') {
      steps {
        build(job: 'HelpDesk_Build', quietPeriod: 5, wait: true)
      }
    }

    stage('Publish') {
      steps {
        sleep 5
      }
    }

    stage('Deploy') {
      steps {
        sleep 5
      }
    }

  }
}
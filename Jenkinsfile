pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        sh ansible-playbook grafana.yml
        }
      }
    stage('second') {
      steps {
        sh ls -l
        sh echo "We are done"
      }
    }
  }
}


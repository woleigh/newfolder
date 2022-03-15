pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        sh 'ansible-playbook grafana.yml'
        }
      }
    stage('second') {
      steps {
        sh 'ls -l'
        echo "We are done"
      }
    }
  }
}


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
        ls -l
        echo "We are done"
      }
    }
  }
}


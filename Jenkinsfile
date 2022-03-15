pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        sh 'ansible-playbook grafana.yml --syntax-check'
        }
      }
    stage('second') {
      steps {
        sh 'ansible-playbook grafana.yml'
        echo "We are done"
      }
    }
    stage('third') {
      steps {
        echo "Hip hop Hooray"
        }
      }
    stage('four') {
      steps {
        echo 'Naughty by Nature'
        }
      }
    }
}


pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(propagate: true, quietPeriod: 5, wait: true, job: 'install')
      }
    }

    stage('deploy') {
      steps {
        sh 'echo $ vamsi'
      }
    }

  }
}
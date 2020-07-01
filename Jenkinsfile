pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'checking out'
      }
    }

    stage('build') {
      steps {
        build(propagate: true, job: 'build')
      }
    }

  }
}
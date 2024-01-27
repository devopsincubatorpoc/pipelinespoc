pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/devopsincubatorpoc/pipelinespoc', branch: 'main', credentialsId: '73f0f829-d2dd-478e-bc77-0a1136155c99')
      }
    }

    stage('build') {
      steps {
        echo 'hello world'
      }
    }

    stage('deploy') {
      steps {
        writeFile(file: 'hello', text: 'building')
      }
    }

    stage('post') {
      steps {
        sleep 2
      }
    }

  }
}
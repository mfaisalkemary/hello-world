pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('build') {
      agent {
        docker {
          image 'maven:3-alpine'
        }

      }
      steps {
        sh '''echo \'hello maven\'
sh \'mvn --version\''''
      }
    }
  }
}
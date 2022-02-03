pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'build'
        sh 'sudo docker compose up -f docker-compose.yaml'
        
      }
    }

  }
}

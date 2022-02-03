pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'build'
        sh 'sudo docker compose up -d docker-compose.yaml'
        
      }
    }

  }
}

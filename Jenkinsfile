pipeline {
  agent none
  stages {
    stage('test') {
      steps {
        sh 'pwd; ls'
        sh 'cd /Users/lia/.jenkins/workspace/tes && ./mnvw jetty:run-war'
      }
    }
    stage('test2') {
      steps {
        sh 'ls'
      }
    }
  }
}
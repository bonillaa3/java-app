pipeline {
  agent any
  stages {
    stage('Maven Deploy') {
      steps {
        sh 'mvn tomcat7:deploy'
      }
    }
  }
}
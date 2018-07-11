pipeline {
  agent any
  stages {
    stage('More Stuff') {
      steps {
        echo 'more stuff'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
    stage('Maven Deploy') {
      steps {
        sh 'mvn tomcat7:deploy'
      }
    }
  }
}
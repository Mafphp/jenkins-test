pipeline {
  agent {
    node {
      label 'master'
    }
  }
  options {
    disableConcurrentBuilds()  //each branch has 1 job running at a time
  } 
  stages {
    stage('clone repository') {
      steps {
      }
    } 
    stage('build composer') {
      steps {
        script {
        }
      }    
    }
    stage('run server'){ 
      steps {
        script {
        }
      }
    }
    stage('warm up'){ 
      steps {
        script {
        }
      }
    }
    stage('server tests') {
      steps {
        script {
        }
      } 
    }
    stage('client build') { 
      steps {
        script {
        }
      }
    }
    
  }
  environment {
  } 
  post {
    unstable {
    }
    failure {
    }
    aborted {
    }
    success {
    }
    cleanup {
    }
  }
}

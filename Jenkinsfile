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
    } 
    stage('build composer') {
    }
    stage('run server'){ 
     
    }
    stage('warm up'){ 
    }
    stage('server tests') {
    }
    stage('client build') { 
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

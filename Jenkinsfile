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
         script {
            sh "echo hello-unstable"
        }
    }
    failure {
         script {
            sh "echo hello-failure"
        }
    }
    aborted {
        script {
            sh "echo hello-aborted"
        }
    }
    success {
         script {
            sh "echo hello-success"
        }
    }
    cleanup {
         script {
            sh "echo hello-cleanup"
        }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo " hello tabbu "'
      }
    }

    stage('stage2') {
      parallel {
        stage('stage2') {
          steps {
            sh 'echo " my name "'
          }
        }

        stage('step1') {
          steps {
            sh 'echo " hostname"'
          }
        }

        stage('step2') {
          steps {
            sh 'echo " this my file"'
          }
        }

      }
    }

  }
}
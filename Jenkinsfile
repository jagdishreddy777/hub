pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "Hii Good morning my Love!!!"'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "Hii Good morning my Love!!!"'
          }
        }

        stage('stage3') {
          steps {
            sh 'echo "Hii Good morning my Love!!!"'
          }
        }

      }
    }

  }
}
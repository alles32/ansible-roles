pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo hallo'
          }
        }

        stage('') {
          steps {
            node(label: 'master') {
              isUnix()
            }

          }
        }

      }
    }

    stage('st2') {
      steps {
        sleep 30
      }
    }

  }
}
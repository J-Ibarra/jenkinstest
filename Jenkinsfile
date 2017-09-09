pipeline {
  agent none
  stages {
    stage('compile') {
      steps {
        parallel(
          "compile": {
            echo 'Hola'
            
          },
          "other": {
            echo '123'
            
          },
          "3222": {
            echo '312'
            
          },
          "1231": {
            echo '123'
            
          },
          "123": {
            echo '1233'

          }
        )
      }
    }
    stage('final') {
      steps {
        echo 'final'
      }
    }
  }
}
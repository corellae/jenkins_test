pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello, this was triggered by scm change, another change'
      }
    }
    stage('goodbye'){
      steps {
        echo 'this is all for triggers, goodbye!'
      }
    }

  }
}

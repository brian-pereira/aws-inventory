pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python2 get_inventory.py --file test.xls --account PREPROD --environment preprod2 '
      }
    }

  }
}
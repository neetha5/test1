pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: '',
          branch: 'main'
      }
    }
    stage('Run Script'){
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}

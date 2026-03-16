pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/neetha5/test1.git',
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

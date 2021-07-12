
pipeline {
  agent none
  stages {
    stage('Deploy') {
      agent any
      steps {
        echo 'Deploying'
        sh "chmod +x -R ${env.WORKSPACE}"
        sh './deploy_jenkins.sh'
      }
    }
  }
}

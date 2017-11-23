pipeline {
  agent any
  stages {
    stage('clone_code') {
      steps {
        git(url: 'https://github.com/CatMi/Jenkins_blue_ocean.git', branch: 'master')
      }
    }
  }
}
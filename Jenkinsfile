pipeline {
  agent any
  tools {
    gradle "Gradle"
  }
  stages{
    stage ('Build gradle app') {
      steps {
        sh 'gradle clean build'
      }
    }
    stage ('Test gradle app') {
      steps {
        sh 'gradle test'
      }
    }
  }
}

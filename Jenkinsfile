pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        bat' javac App.java'
      }
    }
    stage('run'){
      steps{
        bat' java App.java'
      }
    }
  }
}
  

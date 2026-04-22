pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        script{
          def num1=10
          def num2=20
          def sum = num1 + num2
          echo " sum of ${num1} & ${num2} is: ${sum}"
        }
      }
    }
  }
}

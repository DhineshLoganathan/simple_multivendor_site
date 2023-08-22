pipeline{
  agent any
  triggers{
    gitpush()
  }
  stages{
    stage("Checkout"){
      steps{
        checkout scm
      }
    }
  }
}

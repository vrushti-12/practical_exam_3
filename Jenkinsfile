pipeline{
  agent any
  stages{
    triggers{
      POLLSCM(H/5 * * * *)
    }
    stage("Checkout"){
      steps{
        echo "checkout git repo"
        checkout scm
      }
    }
    stage("build"){
      steps{
        echo "Build application executed successfully"
      }
    }
    stage("Test"){
      steps{ 
      echo "Test stage executed successfully"
    }
    }
    }
 } 
        

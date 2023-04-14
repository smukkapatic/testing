pipeline{
agent any
  stages{
    stage("check"){
      when{
          changeRequest()
        }
      steps{
        
        echo "${env.GIT_BRANCH}"
      }
    }
    
  }
}

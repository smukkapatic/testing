pipeline{
agent any
  stages{
    stage("check"){
      steps{
        when{
          changeRequest()
        }
        echo ${env.GIT_BRANCH}
      }
    }
    
  }
}

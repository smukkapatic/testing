pipeline{
 agent { label 'monterey-m1' } 
  stages{
    stage("check"){
      when{
          changeRequest target: 'master', title: 'Test-*', comparator: 'REGEX'
        }
      steps{
        
       echo "${env.GIT_BRANCH}"
        echo "${env}"
      }
    }
    
  }
}

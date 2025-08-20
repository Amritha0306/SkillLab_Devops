pipeline{
 agent any
 stages{
   stage('Checkout'){
     steps{
        git branch: 'master', url:
'git@github.com:Amritha0306/SkillLab_Devops.git'
   }
  }
  stage('Hello'){
    steps{
      echo "hello from Jenkins Pipeline!"
     }
   }
  stage('Goodbye'){
    steps{
      echo "Pipeline finished sucessfully"
       }
     }
    }
   }

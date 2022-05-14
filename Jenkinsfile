pipeline {
agent any

stages {
   stage('SCM') {
     steps {
          echo "git pull my code step 1"
          echo "step 2"
       }
  }

  stage('Deploy') {
     steps {
          echo "deploying my code"
       }
  }

  stage('Test') {
     steps  {
         echo "test my final webapp"
       }
   }

  stage('Deploy to production') {
     steps  {
         echo "webapp deployed to prod"
       }
   }

 }
}
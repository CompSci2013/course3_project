pipeline {
  agent any
  stages {
    stage("Compile"){
      steps{
        sh "mvn compile"
      }
    }
    stage("Unit test"){
      steps{
        sh "mvn test"
      }
    }
    stage("deploy"){
      steps{
        echo "Deploy to Tomcat"
      }
    }
  }
}
   

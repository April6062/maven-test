pipeline {
    agent any
    tools{
     maven "MAVEN_HOME"
    }
     stages{
      stage('Hello'){
       steps {
         echo "Hello World"
       }
    }
    stage("build"){
      steps {
      sh 'mvn clean'  
      }
    }
    
    }

}

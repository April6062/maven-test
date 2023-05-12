pipeline {
    agent any
    tools{
     maven "MAVE_HOME"
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

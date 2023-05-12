pipeline {
    agent any
    tools{
     mave "MAVE_HOME"
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

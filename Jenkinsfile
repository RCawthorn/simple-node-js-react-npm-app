pipeline {
    agent any
    environment{ 
    VERSION = readMavenPom().getVersion()
    }
  stages {

 		stage("version"){
            		steps{
            		   echo "${VERSION}"
            }
		 }
    stage(‘Build’) {
	steps {
		echo "Build successful"
	           }
	 }



	stage (‘Test’) {
	   steps {
		   echo "Test has passed"
		
	          }
			}
          
    
stage('Testing Environment') {
            steps {
                echo "hello"
            }
        }


		}
	   }   

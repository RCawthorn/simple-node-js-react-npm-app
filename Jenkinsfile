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
    stage(‘Build’) {
	steps {
		//…
	           }
	 }



	stage (‘Test’) {
	   steps {
		//…
	          }
			}
          
    
stage('Testing Environment') {
            steps {
                echo "hello"
            }
        }


		}
	   }   

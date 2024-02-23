pipeline {
    agent any
    stages{
	    stage('Git Clone'){
		    steps{
		        git branch: 'main', url: 'https://github.com/Maheshwar2107/TestProject.git'
	    	    }
	        }
	    stage('Build'){
		    steps{
		        echo 'Build on Test Branch Done'		        
		   }
	        }
	   	stage('Test'){
		    steps{
		        echo 'Test on Test Branch Done'
	    	    }
	        }
	   	stage('Deploy'){
		    steps{
		        echo 'Deploy on Test Branch Done'
	    	    }
	        }
	    	   	stage('Publish'){
		    steps{
		        echo 'Publish on Test Branch Done'
	    	    }
	        }
    }
}

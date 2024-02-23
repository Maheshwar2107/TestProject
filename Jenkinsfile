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
		        echo 'Build on Main Done'		        
		   }
	        }
	   	stage('Test'){
		    steps{
		        echo 'Test on Main Done'
	    	    }
	        }
	   	stage('Deploy'){
		    steps{
		        echo 'Deploy on Main Done'
	    	    }
	        }
    }
}

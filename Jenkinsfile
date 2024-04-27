pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/mayur/Documents/DevOps-Software/apache-maven-3.9.6'
	                 }}
		stage('Deployment'){
		   steps {
		sh 'cp target/pipe-project.war /home/mayur/Documents/DevOps-Software/apache-tomcat-9.0.88/webapps'
			}}	
}}

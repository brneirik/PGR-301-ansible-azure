#!groovy
pipeline {
	agent any

	stages{

		stage('Run ansible playbook')  {	
			steps{
				sh 'ansible-playbook azure.yml'
			}
		}
				
	}			
}
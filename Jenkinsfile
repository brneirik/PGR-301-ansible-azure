#!groovy
@Library('fagdagjenkins-shared') _

pipeline {
	agent any

	stages{

		stage('ansible')  {	
			steps{
		   		sh('ansible-playbook azure.yml') 
			}
		}
				
	}			
}
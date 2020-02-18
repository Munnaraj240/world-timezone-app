pipeline
{
	agent any
	stages{
		stage('Build Application'){
		steps{
		bat 'mvn clean install'
		      }
		}
		
		stage('Deploy application to mulesoft Cloudhub'){
		steps{
		bat 'mvn pacakage deploy -DmuleDeploy'
			}
		}
		
	}
}
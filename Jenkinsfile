pipeline{
	agent any
	stages{
		
		stage('Build'){
			steps{
				echo "building"
				sh 'mvn clean'
			}
		}
		stage('Deploy'){
			steps{
				echo "Deploying"
			}
		}
		
	}
}		
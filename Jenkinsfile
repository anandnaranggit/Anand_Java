pipeline{
	agent any
	stages{
		
		stage('Build'){
			steps{
				echo "building"
				mvn clean package
			}
		}
		stage('Deploy'){
			steps{
				echo "Deploying"
			}
		}
		
	}
}		
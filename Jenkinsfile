pipeline{
	agent any
	stages{
		
		stage('Build'){
			steps{
				echo "building"
				sh 'mvn clean package'
			}
		}
		stage('Deploy'){
			steps{
				echo "Deploying"
			}
		}
		
	}
}		
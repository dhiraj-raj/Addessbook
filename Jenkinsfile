pipeline{
    agent {lable 'node-mvn'}
	stages{
		stage ('Build mvn-project'){
			steps{
				sh 'mvn compile'
			}
		}
		stage ('Test mvn project'){
			steps{
				sh 'mvn test'
			}
		}
	}	
}

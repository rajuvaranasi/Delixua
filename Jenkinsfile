pipeline {
    agent any
    stages {
        stage ('package stage') {
            steps {
			node ('buildagent') {
                           sh label: '', script: 'sudo mvn clean package'
		   }
			              
            }
        }
    }
}

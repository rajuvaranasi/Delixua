pipeline {
    agent any
    stages {
        stage ('package stage') {
            steps {
			node ('master') {
                           sh label: '', script: 'sudo mvn clean package'
		   }
			              
            }
        }
    }
}

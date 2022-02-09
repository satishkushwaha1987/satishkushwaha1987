 node {
    	stage('SCM Checkout'){
            checkout scm
    }
	stages {
        	stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

	

node {
    stage('SCM Checkout'){
	    checkout scm
    }
    stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
}	

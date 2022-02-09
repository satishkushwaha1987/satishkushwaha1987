node {
   stage('SCM Checkout'){
	    checkout scm
	 }
   stage('Build') { 
                (mvn -B -DskipTests clean package)
                }
}

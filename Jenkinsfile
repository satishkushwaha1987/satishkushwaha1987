node {
   stage('SCM Checkout'){
	    checkout scm
	 }
   stage('Build') { 
                sh 'mvn -B -DskipTests clean package'
                }
}

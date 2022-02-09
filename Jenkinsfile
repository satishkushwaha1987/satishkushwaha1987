node {
    stage('SCM Checkout'){
	    checkout scm
    }
    stage('docker'){
        	sh image 'maven:3.8.1-adoptopenjdk-11' 
            	sh args '-v /root/.m2:/root/.m2
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

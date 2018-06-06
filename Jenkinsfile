pipeline {
    
    agent { label 'vps0005.nazwa.pl' }
    
    
    stages {
    
	stage ('checkout...') {
	    echo "checkout"
	}

	
	stage ('build') {
	    echo "build"
	}
	

	stage ('test') {
	    echo "test"
	}
	
	
	stage ('package') {
	    echo "package"
	}
	
	
    }
    
    post {
	
	always {
	    echo "post section..."
	}
    }
    
}

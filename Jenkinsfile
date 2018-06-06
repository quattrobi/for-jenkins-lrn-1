pipeline {
    
    agent { label 'vps0005.nazwa.pl' }
    
    
    stages {
    
	stage ('checkout...') {
	    steps {
		echo "checkout"
	    }
	}

	
	stage ('build') {
	    steps {
		echo "build"
	    }
	}
	

	stage ('test') {
	    steps {
		echo "test"
	    }
	}
	
	
	stage ('package') {
	    steps {
		echo "package"
	    }
	}
	
	
    }
    
    post {
	
	always {
	    echo "post section..."
	}
    }
    
}

pipeline {
    agent any

    stages {
        stage(“build”) {
	steps {
	    echo 'Building the application'

	}
        }

        stage(“test”) {
	steps {
	    echo 'Testing the application'
		
	    script {
	        def test = 2 + 2 > 3 ? 'cool' : 'not cool'
	        echo test
	    }
	}
        }

        stage(“deploy”) {
	steps {
	    echo 'Deploying the application'

	}
        }
    }
}

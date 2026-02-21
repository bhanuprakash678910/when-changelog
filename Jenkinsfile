pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                changelog '.*JIRA-.*'
	    }
            steps {
                echo "Hello World changelog"
            }
        }
    }
}

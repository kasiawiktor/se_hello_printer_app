pipeline {
    agent any
    stages {
        stage('Deps') {
           steps {
	                 sh 'make deps'
		             }
        stage('Linter') {
            steps {
                   sh 'make Linter'
                          }
    }
	      stage('Test') {
	          steps {
		               sh 'make test'
		          }
    }
  }
}

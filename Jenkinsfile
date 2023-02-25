// DEclarative pipeline syntax

pipeline{
	agent any
	stages{
		stage('Build'){
			echo "Build"
		}
	}
	stages{
		stage('Test'){
			echo "Test"
		}
	}
	stages{
		stage('Implement'){
			echo "Implement"
		}
	}
}

Post{
	always{
		echo "I'm awesome. I run always"
	}
	success{
		echo "I run when you are successful"
	}
	failure{
		echo "I run when you fail"
	}
}

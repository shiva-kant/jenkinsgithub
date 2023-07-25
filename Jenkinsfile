pipeline{
	agent none
	stages{

	stage('one'){
        steps{
        agent {label 'labelone'}
        echo "label ONE"
        }
        }
        stage ('two'){
        steps{
        agent {label 'label3'}
        echo "LABEL 3 Added after "
        }
        }
	}
	}

pipeline{
	agent none
	stages{
parallel {
	stage('one'){
        steps{
        agent {label 'labelone'}
        echo "label ONE"
        }
        }
        stage ('two'){
        steps{
        agent {label 'label2'}
        echo "LABEL 2"
        }
        }
        }
	}
	}

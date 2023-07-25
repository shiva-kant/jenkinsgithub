pipeline{
	agent none
	stages{

    parallel{
       stage('stageone'){
          agent {label 'labelone'}
         steps{
         echo "Hello label One"
         }

    }
stage('stagetwo'){
          agent {label 'label2'}
         steps{
         echo "Hello label Two"
         }

    }
	}
}

}

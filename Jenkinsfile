pipeline {
    agent none
    
    stage('parallel'){
    parallel{
        
        stage('two'){
            agent{
                label 'labelone'
            }
            steps{
                echo "Hello @LABEL 1"
            }
        }
        stage('three'){
            agent{
                label 'label2'
            }
            steps{
                echo "Hello @label 2"
            }
        }
    }
    }
}

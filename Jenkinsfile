papeline{
    agent none

    stages{

stage("parallelpipe")
{
    parallel{

        stage("one"){
        agent {label 'labelone'}
        steps {
        echo "Hello Label One"
        }
        }
stage("three"){
        agent {label 'label3'}
        steps {
        echo "Hello Label 3"
        }
        }

    }

}


    }
}

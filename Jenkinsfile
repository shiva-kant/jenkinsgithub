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
stage("two"){
        agent {label 'label2'}
        steps {
        echo "Hello Label 2"
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

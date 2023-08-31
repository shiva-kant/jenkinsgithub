
pipeline{
    agent any

    stages{

stage("parallelpipe")
{
    parallel{

        stage("one"){
        
        steps {
        echo "Hello Label One"
        }
        }
stage("two"){
        
        steps {
        echo "Hello Label 2"
        }
        }


}


    }
}
}

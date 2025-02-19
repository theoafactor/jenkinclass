pipeline {
    agent any
    stages{

        stage("initial-stage"){
            steps{
                sh `
                    echo "Hello, this is the initial-stage"
                    mkdir "sample_dir" 
                `
            
            }
        }

        stage("building-stage"){

             steps{
                sh 'echo "Hello, this is the building-stage"'
            }

        }

        stage("production-stage"){
             steps{
                sh 'echo "Hello, this is the production-stage"'
            }

        }



    }


}
pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Building"
            }
            post{
            success{
                mailto: "sylvester25r@gmail.com"
                subject: "Build Status Email "
                body: "Body was successful!"
            }
                }   
            }
    }
}
pipeline{
    agent any
    stages{
        stage("BUILD"){
            when{
                 tag "release -  *"
            }
            steps{
                echo "Hello World Buildong Tag"
            }
        }
    }
}

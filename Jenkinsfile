pipeline{
    agent any
    stages{
        stage("BUILD"){
            when{
                buildingTag()
            }
            steps{
                echo "Hello World Buildong Tga"
            }
        }
    }
}

pipeline{
    agent any 

    environment {
        AUTHOR_NAME = "OUMAR"
    }

    stages{
        stage("build de l'application ..."){
            steps{
                echo "BRANCH_NAME : ${ BRANCH_NAME }"
                echo "AUTHOR_NAME : ${ AUTHOR_NAME }"
            }
        }
    }
}
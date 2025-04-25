pipeline{
    agent any 

    environment{
        AUTHOR : "OUMAR"
    }

    stages{
        stage("build de l'application"){
            steps{
                echo "BRANCH_NAME ${ BRANCH_NAME }"
                echo "BRANCH_IS_PRIMARY ${ BRANCH_IS_PRIMARY }"
                echo "TAG_TIMESTAMP ${ TAG_TIMESTAMP }"
                echo "AUTHOR ${ AUTHOR }"
            }
        }
    }
}
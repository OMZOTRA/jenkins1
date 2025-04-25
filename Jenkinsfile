pipeline{
    agent any 

    environment{
        AUTHOR : "OUMAR"
    }

    stages{
        stage("build de l'application"){
            steps{
                echo "BRANCH_NAME :  ${env.BRANCH_NAME}"
                echo "BRANCH_IS_PRIMARY : ${env.BRANCH_IS_PRIMARY}"
                echo "TAG_TIMESTAMP :  ${env.TAG_TIMESTAMP}"
                echo "AUTHOR :  ${AUTHOR}"
            }
        }
    }
}
pipeline{
    agent any 

    environment {
        AUTHOR : 'OUMAR'
        NUMBER : 'O3648'
    }

    stages{
        stage('build'){
            steps{
                echo "BRANCH_NAME : ${ BRANCH_NAME }"
                echo "BRANCH_IS_PRIMARY : ${ BRANCH_IS_PRIMARY }"
                echo "TAG_TIMESTAMP : ${ TAG_TIMESTAMP }"
                echo "AUTHOR:  ${ AUTHOR }"
                echo "NUMBER:  ${ NUMBER }"
            }
        }
    }
}
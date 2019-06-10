pipeline {
    agent any
    echo "current branch: $BRANCH_NAME"
    stages {
        stage ('Compile Stage') {
            when {
                expression { $BRANCH_NAME =='master'}
            }
            steps {
                print("master")
            }
            when {
                expression { $BRANCH_NAME =='master'}
            }
            steps {
                print("trex")
            }
        }
    }
}

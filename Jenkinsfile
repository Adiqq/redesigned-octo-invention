pipeline {
    triggers{
        pollSCM('*/5 * * * *')
    }
    agent {
        label ""
    }
    stages {
        stage("build"){
            steps{
                echo "building"
            }
        }
        stage("deploy"){
            steps{
                echo "deploying"
            }
        }
    }
}

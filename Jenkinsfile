pipeline{
    agent any
        stages{
            stage('1-Main Branch deploy Code'){
                when {
                    branch 'main'
                }
                steps{
                    sh ' echo "building Artifact from main" '
                    echo " Deploying code from main branch"
                    echo " this is done by Bolatito"
                    echo " my first pull request to demo this project"
                }
            }
                stage ('develop branch delpoy code'){
                    when {
                        branch 'develop'
                    }
                    steps{
                        sh ' echo "building artifacts from develop branc" '
                        sh 'echo "deploying code from develop branhc" '
                     
                    }
                }
        
    }
}

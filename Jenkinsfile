node {
    stage('masterRun') {
        if(env.BRANCH_NAME == 'master') {
            echo "Master will get execute"
        } else {
            echo "Develop will get execute"
            ["git", "clone", "https://github.com/Giritharan92/time-tracker.git"].execute()
        }
    }
}

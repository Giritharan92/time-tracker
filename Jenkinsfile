node {
    stage('SCM Checkout'){
        
        git 'https://github.com/Giritharan92/time-tracker.git'
    }
    stage('Check MVN version'){
        def mvnHome = tool name: 'Maven-3.2.5', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        sh 'mvn -version'
    }
}

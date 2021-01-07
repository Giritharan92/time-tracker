node {
    stage('SCM Checkout'){
        
        git 'https://github.com/Giritharan92/time-tracker.git'
    }
    stage('Compile-Package'){
        def mvnHome = tool name: 'Maven-3.2.5', type: 'maven'
        sh 'mvn --version'
        //sh "${mvnHome}/bin/mvn package"
        //sh 'mvn package'
    }
}

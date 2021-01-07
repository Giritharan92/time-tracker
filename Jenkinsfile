node {
    stage('SCM Checkout'){
        git 'https://github.com/Giritharan92/time-tracker.git'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}

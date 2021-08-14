node{
    stage('SCM Checkout') {
        git 'https://github.com/encore-tvm/jenkins-projects'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}

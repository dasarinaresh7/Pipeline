node{
  stage('SCM Checkout'){
git 'https://github.com/dasarinaresh7/Pipeline/'
}
stage('Compile-Package'){
//Get maven home path
def mvnHome = tool name: 'MAVEN 3', type: 'maven'
bat "${mvnHome}/bin/mvn package"
}
}

node{
  stage('SCM Checkout'){
git 'https://github.com/dasarinaresh7/Pipeline/'
}
stage('Compile-Package'){
//Get maven home path
def mvnHome = tool name: 'maven-3', type: 'maven'
bat "${mavnHome}/bin/mvn package"
}
}

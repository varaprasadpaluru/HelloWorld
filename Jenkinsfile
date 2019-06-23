node {
  stage('SCM Checkout') {
    git 'https://github.com/varaprasadpaluru/HelloWorld'
  }
  stage('Compile Package')
  {
    // Define maven home path
    def mavenHome = tool name : 'maven-3',type :'maven'
    sh "${mavenHome}/bin/mvn package"
  }
}

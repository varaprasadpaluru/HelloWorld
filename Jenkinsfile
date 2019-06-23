node {
  stage('SCM Checkout') {
    git 'https://github.com/varaprasadpaluru/HelloWorld'
  }
  stage('Compile Package')
  {
    // Define maven home path
    def mavenHome = tool type :'maven'
    sh "${mavenHome}/bin/mvn package"
  }
}

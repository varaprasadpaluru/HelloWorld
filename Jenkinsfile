node {
  stage('SCM Checkout') {
    git 'https://github.com/varaprasadpaluru/HelloWorld'
  }
  stage('Compile Package')
  {
    sh 'mvn package'
  }
}

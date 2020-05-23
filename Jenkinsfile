node{
  stage('SCM Checkout'){
    git 'https://github.com/sullururamesh/genkinsbuild'
  }
  echo 'Ramesh'
  stage('Compile-Package')
  {
   def mavenHome=tool name: 'maven', type: 'maven'
    sh "${mavenHome}/bin/mvn package"
  }
}

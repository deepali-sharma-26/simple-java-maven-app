node {
stage('SCM-Checkout'){
git 'https://github.com/deepali-sharma-26/simple-java-maven-app' }
stage ('compile-package')
{ def mvnhome=tool name:'mymaven',type: 'maven'
sh "${mvnhome}/bin/mvn clean install "
}
}

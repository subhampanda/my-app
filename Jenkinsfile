node{
    stage('SCM checkout'){
     git 'https://github.com/subhampanda/my-app.git'
    
    }
    stage('compile-package'){
    sh 'mvn package'
    }
    stage('compile-package'){
    sh 'mvn sonar:sonar'
    }
    
}

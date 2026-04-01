node {
    stage('git-clone') {
        git branch: 'main', url: 'https://github.com/Sarath0505/spring-framework-petclinic.git'
    }
    stage('build') {
        sh 'mvn package'
    }
}

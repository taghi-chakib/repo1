node {
    
    stage('clone') {
        git 'https://github.com/taghi-chakib/repo1.git'
    
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    
    }
    stage('run') {
        sh label: '', script: 'java Main'
    
    }
}

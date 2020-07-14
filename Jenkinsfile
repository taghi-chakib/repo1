node {
    
    stage('clone') {
        git 'https://github.com/taghi-chakib/repo1.git'
    
    }
    stage('build') {
        sh label: '', script: 'javac MAIN.JAVA'
    
    }
    stage('run') {
        sh label: '', script: 'java MAIN'
    
    }
}


node {
    stage('clone') {
        git 'https://github.com/marlincia/hello.git'
    }
    stage('Build') {
        sh 'wc -l helloworld'
    }
    stage('Run') {
        sh 'cat helloworld'
    }    
}

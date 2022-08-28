node {
    stage('clone') {
        git 'https://github.com/marlincia/hello.git'
    }
    stage('Build') {
        sh 'cd hello && ls -rlht'
    }
    stage('Run') {
        sh 'cat helloworld'
    }    
}

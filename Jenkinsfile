node {
    stage('clone') {
        git 'https://github.com/marlincia/hello.git'
    }
    stage('Build') {
        sh 'ls -rlth hello'
    }
    stage('Run') {
        sh 'cat hello/helloworld'
    }    
}

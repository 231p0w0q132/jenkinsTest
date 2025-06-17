node {
    stage('git clone') {
        git branch: 'main', url: 'https://github.com/231p0w0q132/jenkinsTest.git'
    }
    stage('Test') {
        echo 'Testing....'
    }
    stage('execute sh') {
		sh "chmod 774 ./project.sh"
        sh "./project.sh"
    }
}

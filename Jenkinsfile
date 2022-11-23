node {
    stage('checking git version'){
        cleanWs()
        sh 'git --version'
    }
    stage('pulling from git'){
        git 'https://github.com/octocat/Hello-World.git'
    }
    stage('build'){
        
        sh 'cat README'
    }
}
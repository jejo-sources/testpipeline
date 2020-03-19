
node {
    stage('Clone') {
        git 'https://github.com/jejo-sources/testpipeline'
    }
    stage('Build') {
        sh label: '', script: 'javac TestPipeline.java'
    }
    stage('Run') {
        sh label: '', script: 'java TestPipeline'
    }    
}

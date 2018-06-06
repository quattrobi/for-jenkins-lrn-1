node {
    echo "dupa"
}

node ('vps0003.nazwa.pl') {
    stage('checkout 1') {
        git 'https://github.com/quattrobi/for-jenkins-lrn-1.git'
    }

    stage('run checked out...') {
        sh './some-script.sh'
    }

    stage('my stage 1') {
        echo "123 dupa"
        sh 'echo "dupa"'
        sh '''
            echo "1"
            echo "2"
            echo "3"
            echo "dupa2" > file-2.txt
            cp file-2.txt file-2-copy.txt
        '''
    }
}

node('vps0004.nazwa.pl') {
    stage('my stage 2') {
        echo "asdf 2"
    }
}

node('vps0005.nazwa.pl') {
    stage('my stage 3') {
        echo "zxcv 3"
    }
}



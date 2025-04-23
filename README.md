Windows
```
pipeline {
   agent any
    stages {
        stage('build') {
            steps {
                bat 'python -V'
            }
        }
    }
}
```

Linux
```
pipeline {
   agent any
    stages {
        stage('build') {
            steps {
                sh 'python -V'
            }
        }
    }
}

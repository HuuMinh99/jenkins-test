pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}" // chỗ này sẽ in ra console là "Hello anh Long" nếu ta truyền biến PERSON=anh Long vào
            }
        }
    }
}
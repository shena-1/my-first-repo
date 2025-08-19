pipeline {
agent any
stages {
stage('Build') {
steps {
echo 'Building the application...'
// Add your build commands here (e.g., mvn clean

install)
}
}
stage('Test') {
steps {
echo 'Running tests...'
// Add your test commands here (e.g., mvn test)
}
}
stage('Deploy') {
steps {
echo 'Deploying the application...'
// Add your deployment commands here (e.g., deploy

to S3, ECS, etc.)
}
}
}
}

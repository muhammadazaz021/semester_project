
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building App...'
               // sh  'node --version'
            }
        }
        stage('Deploying') {
            steps {
                echo 'Deploying App...'
               // sh 'node App.js'
                //sh 'gcloud compute zones list'
                sh 'gcloud compute scp /var/lib/jenkins/workspace/semester_project_main/index.html root@azaz-instance-20240521-081701:/var/www/html --zone=us-central1-a'
               // sh 'gcloud compute scp /var/lib/jenkins/workspace/Assignment-4_main/projects.html root@apache-server:/var/www/html --zone=us-central1-f'
                //sh 'gcloud compute scp /var/lib/jenkins/workspace/Assignment-4_main/about.html root@apache-server:/var/www/html --zone=us-central1-f'
                //sh 'gcloud compute scp /var/lib/jenkins/workspace/Assignment-4_main/contact.html root@apache-server:/var/www/html --zone=us-central1-f'
            }
}
}
}

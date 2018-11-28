pipeline{
agent {docker 'maven:3.5-alpine'}

stages {

stage('Checkout'){
steps{
git 'https://github.com/dsrdsr8/git_pet_Clinic.git'
}
}

stage('Build'){
steps{
sh 'mvn clean package'
}
}

}

}

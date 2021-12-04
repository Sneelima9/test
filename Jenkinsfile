pipeline{

agent{

label 'Ubuntu-slave'

}

stages{

stage('checkout')
{ 
steps{

    checkout scm

}

}

stage('successfull execution')
{
step{
    echo "checkout has been done"
}
}
}


}

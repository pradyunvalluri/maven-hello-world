def workspace;
node
{
    stage('checkout')
    {
       git 'https://github.com/pradyunvalluri/maven-hello-world.git' 
       workspace =pwd()
    }
    stage('static code analysis')
    {
     echo "static code analysis"   
    }
    stage('build')
    {
     echo "build the code"    
    }
    stage('unit test')
    {
     echo "unit testing stage"   
    }
    stage('deliver')
    {
     echo "delivery stage"   
    }
    stage('see value in pwd')
    {
     echo $PWD   
    }
    
}

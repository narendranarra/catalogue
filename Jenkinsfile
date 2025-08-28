@Library('jenkins-shared-library') _

def configMap = [  
    greeting = "Hello Jenkins"
]
samplePipeline(configMap)

/* @Library('jenkins-shared-library') _

def configMap = [                              // here is jenkins configmap maps means key value pair
    project : "roboshop",
    component: "catalogue"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
    nodejsEKSPipeline(configMap) // by default it will call, call function inside this pipeline
}
else{
    echo "Please proceed with PROD process"
} */
# How to use jenkins in openshift

First create template use template directory 
eg: oc create -f template/jenkins-persistent.yaml

Then you  must crate a pvc

Finally you can move to web to deploy jenkins, you can replace image with your own jenkins image ,default is redhat's image

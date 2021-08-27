# Simple Terraform Jenkins example  
  
![](images/Jenkins-Loves-Terraform.png?raw=true) 
  
  


Provides a simple implementation of Terraform main.tf file.  
Jenkinsfile is provided as an example pipeline build to execute  
the automated build using the Jenkins Terraform plugin.  
[Plugin](https://plugins.jenkins.io/terraform/)

## Installation

Use of the plugin is documented in many Medium.com articles  
[Medium](https://medium.com/search?q=Terraform%20Jenkins)  
The configuration of the location of your Terraform installation  
will be dependant based on system OS providing a link to assist  
[Install](https://learn.hashicorp.com/tutorials/terraform/install-cli)

## Usage
Install the plugin on the Jenkins server, clone the repo and modify   
the main.tf file as you see fit,  
utilize the Jenkinsfile as a pipeline job in Jenkins  
being sure to modify line 9 off the code to point to your  
specific git code repository


## License
[MIT](https://choosealicense.com/licenses/mit/)

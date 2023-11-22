# azure-javaee-iaas-workflows

## Prerequisites
Run the [setup-credentials.sh](.github%2Fworkflows%2Fsetup-credentials.sh) to set the credentials to run workflows[workflows](.github%2Fworkflows).


## Workflow list

### Provision Workflows
[azure-resource-provision-postgresql.yaml](.github%2Fworkflows%2Fazure-resource-provision-postgresql.yaml)  
This workflow is used to provision an azure postgresql resource to test use.  
By default, it will be destroyed in 60 minutes.  


### Weblogic Domain On PV Sample Workflows  
[weblogic-java8-oracal-wko-sample-storage.yaml](.github%2Fworkflows%2Fweblogic-java8-oracal-wko-sample-storage.yaml)  
[weblogic-java11-oracal-wko-sample-storage.yaml](.github%2Fworkflows%2Fweblogic-java11-oracal-wko-sample-storage.yaml)  
[weblogic-java17-oracal-wko-sample-storage.yaml](.github%2Fworkflows%2Fweblogic-java17-oracal-wko-sample-storage.yaml)  
  
These are workflows to create an domain on PV instance with different JDK and weblogic versions.  
By default, it will be destroyed in 60 minutes.



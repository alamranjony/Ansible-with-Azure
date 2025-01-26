Ansible is an *open-source* product that automates 
- cloud provisioning
- configuration management
- application deployments

Using Ansible you can provision virtual machines, containers, and network and complete cloud infrastructures. Also, Ansible allows you to automate the deployment and configuration of resources in your environment.


## Ansible playbooks
Ansible playbooks allow you to direct Ansible to configure your environment. Playbooks are coded using YAML so as to be human-readable. The Tutorials section gives many examples of using playbooks to install and configure Azure resources.

## Ansible modules
Ansible includes a suite of Ansible modules that are run directly on remote hosts or via playbooks. Users can create their own modules. Modules are used to control system resources - such as services, packages, or files - or execute system commands.

For interacting with Azure services, Ansible includes a suite of Ansible cloud modules. These modules enable you to create and orchestrate your infrastructure on Azure.

## Migrate existing workload to Azure
Once you use Ansible to define your infrastructure, you can apply your application's playbook letting Azure automatically scale your environment as needed.

## Automate cloud-native application in Azure
Ansible enables you to automate cloud-native applications in Azure using Azure microservices such as Azure Functions and Kubernetes on Azure.

## Manage deployments with dynamic inventory
Using the Ansible dynamic inventory feature, you can pull inventory from Azure resources. You can then tag your existing Azure deployments and manage those tagged deployments through Ansible.

## Ansible module and version matrix for Azure
Ansible includes a suite of modules for use in provisioning and configuring Azure resources. These resources include virtual machines, scale sets, networking services, and container services. The Ansible matrix lists the Ansible modules for Azure and the Ansible versions in which they ship.
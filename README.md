# Tech Challenge App

This repo is used to host the Servian Technical Challenge Application. It is comprised of an AWS CloudFormation template that will create the required resources in order to deploy and host the application.

## Usage

Please utilise this CloudFormation template to create a database and instance so that the Servian Technical Challenge App can be deployed.

Please note that DNS records will have to be updated manually at the moment.

## Initial Plans

I had initially planned to use Ansible in order to deploy the infrastructure required for the application, however, I was unable to complete the setup of an Ansible environment in time.

It would function very similarly to the current template, however, would allow for a much easier way to update the Route 53 DNS, while still remaining one playbook. 


## Improvements

Tasks that have not been implemented yet, but will be corrected in the future.

```bash
Currently working on:
  1. Update DNS to automatically point to new servers
```



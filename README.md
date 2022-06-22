# deploy-managedkube-resource

## Context:
Terragrunt keep your terraform code DRY read docs: https://terragrunt.gruntwork.io/
Managed kube is an stack like our customer: https://github.com/ManagedKube; has aws modules just for consume and create resources here: https://github.com/ManagedKube/kubernetes-ops/tree/main/terraform-modules/aws

A generic environment could be the following components https://github.com/ManagedKube/kubernetes-ops/tree/main/terraform-environments/aws/terragrunt-dev/us-east-1/terragrunt-dev. (That is to say that this is the way in which the modules are consumed.)



## Instructions:

- Create a branch of this project and start 
- Take only the following componentes and try to build a new environment; (could be copy paste)
  - 100-route53-hostedzone
  - 150-vpc
  - 200-eks
  - 250-eks-cluster-autoscaler

- Create a new aws account or use an existing one.
- Deploy the components in the region of your choice.
- Attach in the pr evidence of proof 
  - terragrunt plan or apply
  - pictures about how resources are looked at in aws
- Create a pr as detailed as possible and posted it by mattermost.
  - In the pr pod we could interact with comments, possible commit suggestion, etc.

## Extras:
- If you are not familiar with terragrunt you could create your own terraform resources and consume them. 
- Try to deliver something, even if you don't works with properly.

## What is being evaluated?:
- Conventions
- Standars
- How quickly you adapt to a new technology.
- Communication.
- How to get out of a stuck?
- Detail of the work



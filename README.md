# SANS Continuous Security: Monitoring and Active Defense Templates

## Infrastructure Stack

Files were modified from the original:

- Master template was updated to use t2.small instances (for pen testing permission) 
- Application stack was removed to avoid creating the default wordpress stack because it used the classic ELB.

Original project can be found [here](https://s3.amazonaws.com/quickstart-reference/enterprise-accelerator/pci/latest/templates/main.template)

## WAF Stack

Deployed the CloudFront WAF stack to protect the web apps.

https://s3.amazonaws.com/solutions-reference/aws-waf-security-automations/latest/aws-waf-security-automations.template

# Wordpress Stack

Files were modified from the original

- Removed the creation of the bastion stack (already exists in the PCI infrastructure)
- Removed the creation of the vpc stack (already exists in the PCI infrastructure)

Original can be found [here](https://github.com/awslabs/aws-refarch-wordpress)
# Terraform-Configs
Contains all the code to set up my AWS environment

# Terraform Modules

Terraform modules allow you to better organize your configuration code and make the code reusable.
These modules can be hosted on git or in a Terraform Registry.

## Getting Started

This section will describe general use case of our custom modules from input variables to general layout of the main,provider and variables ft files

Module Input Variables
----------------------

- `lab`                - The environment in whitch the resource will be created.
- `security_group`     - The name of the security group the resouce will be attached to.
-  `uuid`              - The network I.D that the resource will be associated with.
-  `external-network`  - The name of the floating I.P address pool for the project.
-  `zone`              - The dns zone which the entry for the instance will be added to
-  `source`            - Describes the place where the  module is hosted

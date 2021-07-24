# terraform-associate-study
Study notes and code for studying for terraform associate

## Introduction to Infrastructure as Code with Terraform

IaC tools are able to provide the capability to manage infrastructure through configuration files rather than through the use of UI.

Capabilities that it adds to infrastructure management include:

- Version control of infrastructure changes
- Repeatable builds
- Peer review of all infrastructure changes
- Consistency

Terraform is Hashicorps version of a IaC tool. It has the following features:

- Multiple provider support
- Human readable configuration language
- State management features to track resource changes
- Commitable to allow safe collaboration on infrastructure

In addition, terraform allows for custom providers to be written so that any deployment target can be used.

Terraform is configured with a declarative syntax. That is, it describes the end-state for your infrastructure rather than how to get there. Order of operations is decided by calculated dependencies between the different resources being managed by terraform.

Steps to deploy infrastructure with Terraform:

- Scope: Identify the infrastructure for your project
- Author: Write the configuration of the infrastructure
- Initialize: Install the plugins Terraform needs to manage the infrastructure
- Plan: Preview the changes about to be made to match the configuration
- Apply: Make the planned changes.


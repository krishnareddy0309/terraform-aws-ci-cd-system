# CI-CD system on AWS ECS Fargate

Test Continuous Integration/Delivery environment on AWS ECS.

[![](https://github.com/cn-terraform/terraform-aws-ci-cd-system/workflows/terraform/badge.svg)](https://github.com/cn-terraform/terraform-aws-ci-cd-system/actions?query=workflow%3Aterraform)
[![](https://img.shields.io/github/license/cn-terraform/terraform-aws-ci-cd-system)](https://github.com/cn-terraform/terraform-aws-ci-cd-system)
[![](https://img.shields.io/github/issues/cn-terraform/terraform-aws-ci-cd-system)](https://github.com/cn-terraform/terraform-aws-ci-cd-system)
[![](https://img.shields.io/github/issues-closed/cn-terraform/terraform-aws-ci-cd-system)](https://github.com/cn-terraform/terraform-aws-ci-cd-system)
[![](https://img.shields.io/github/languages/code-size/cn-terraform/terraform-aws-ci-cd-system)](https://github.com/cn-terraform/terraform-aws-ci-cd-system)
[![](https://img.shields.io/github/repo-size/cn-terraform/terraform-aws-ci-cd-system)](https://github.com/cn-terraform/terraform-aws-ci-cd-system)

## Tools included

* Jenkins
    - Source Code: <https://github.com/cn-terraform/terraform-aws-jenkins>
    - Terraform Module: <https://registry.terraform.io/modules/cn-terraform/jenkins/aws>
* SonarQube
    - Source Code: <https://github.com/cn-terraform/terraform-aws-sonarqube>
    - Terraform Module: <https://registry.terraform.io/modules/cn-terraform/sonarqube/aws>

## Use this code as a Terraform module

Check valid versions on:
* Github Releases: <https://github.com/cn-terraform/terraform-aws-ci-cd-system/releases>
* Terraform Module Registry: <https://registry.terraform.io/modules/cn-terraform/ci-cd-system/aws>

## Deploy CI/CD Infrastructure standalone

1. Clone this repository.

2. To download required plugins and modules run:

        terraform init

3. To update dependencies run:

        terraform get --update

4. To plan a deployment and check what is going to change run:

        terraform plan

5. To deploy changes run:

        terraform apply

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

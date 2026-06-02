# aws-terraform-network-basics

AWS Terraform Network Basics
This repository contains a minimal Terraform configuration demonstrating core AWS networking concepts:

- VPC

- Subnets

- Route Tables

- Internet Gateway

- NAT Gateway

- Basic routing logic

----------------------------------------------------------------------------------

The goal is to show:

- understanding of AWS network building blocks

- ability to structure Terraform code

- clean, modular IaC mindset

- readiness for cloud‑native networking work

This repo is intentionally simple and focused on clarity.

----------------------------------------------------------------

Contents
- main.tf — core AWS networking resources

- variables.tf — input variables

- outputs.tf — exported values

- examples/simple_vpc/ — example usage of the module

-----------------------------------------------------------------

Skills Demonstrated
- Terraform basics

- AWS VPC design

- Subnetting

- Route table creation

- Internet/NAT gateway usage

- IaC structure and readability

----------------------------------------------------------------
How to use:
- cd examples/simple_vpc
- terraform init
- terraform plan

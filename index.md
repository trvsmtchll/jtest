---
title: Aviatrix Terraform Solutions
subtitle: Welcome to Aviatrix Terraform Solutions!
layout: page
show_sidebar: false
---

## Summary

This repository contains various examples of Aviatrix solutions integral to **MCNA (Multicloud Network Architecture)** implemented with Terraform. In general this is intended to assist you with building **_what you need_** or getting very close in the **_shortest_** amount of time.

## Prerequisites

- Understanding of Terraform, how to setup your environment to use it and the Terraform workflow ```init, plan, apply, destroy```
- Understanding of the files associated with Terraform, including ```main.tf, variables.tf, terraform.tfvars``` and how to make changes needed for your requirements.

## Getting Started

If you are new to Aviatrix the first thing you will need to do is launch a Controller. You may be operating in one Cloud today most organizations plan to operate in many *(Multicloud)*. Typically organizations will have a *Primary* Cloud where governance and other shared processes are centralized in. Wherever you are (AWS,Azure,OCI,GCP) is fine. 

**One** Controller is all you need to deploy the solutions.

Take a look in the [controller-launch](./controller-launch) directory and launch one yourself.

## Solutions

Aviatrix has a number of workflows to achieve advanced Cloud Networking configurations AKA **(use cases)**. You can read more about them [here](https://docs.aviatrix.com/) or attend one of our live [events](https://aviatrix.com/events/).

The definition of a **Solution** in the scope of this repository is the Terraform code required to implement one or more of the **use cases** available through the [Aviatrix Terraform Provider](https://www.terraform.io/docs/providers/aviatrix/index.html).

To implement any of the **Solutions** you will need to launch a Controller **first**.





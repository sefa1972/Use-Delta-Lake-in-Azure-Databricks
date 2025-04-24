# Delta Lake in Azure Databricks (DP-203 Lab)

This project is part of the Microsoft Learn DP-203: Data Engineering on Microsoft Azure learning path. It demonstrates how to use **Delta Lake** with **Azure Databricks** to enable transactional storage and querying in a lakehouse architecture.

## Overview

In this lab, I:

- Provisioned an Azure Databricks workspace using PowerShell via Azure Cloud Shell.
- Created a Spark cluster with Databricks Runtime 13.3 LTS.
- Explored Delta Lake functionality by importing and running a Databricks notebook.

## Steps Followed

### 1. Azure Setup

- Signed into the [Azure Portal](https://portal.azure.com).
- Opened PowerShell in Azure Cloud Shell.
- Cloned the lab files:

  ```powershell
  rm -r dp-203 -f
  git clone https://github.com/MicrosoftLearning/dp-203-azure-data-engineer dp-203
  cd dp-203/Allfiles/labs/25
  ./setup.ps1

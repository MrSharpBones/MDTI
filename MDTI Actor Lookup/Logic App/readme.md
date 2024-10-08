# Infrastructure Chaining Automation with Logic App and Function App

## Introduction

This project demonstrates the automation of Infrastructure Chaining using a Logic App that triggers a Function App. The primary goal is to streamline the process of threat intelligence, making it more efficient and reliable.

![basic visio](https://github.com/user-attachments/assets/91d0419e-97be-48f3-9f51-07f0f36347ca)

## Features

- **Automated Workflow**: Utilizes Azure Logic Apps to automate the chaining process.
- **Function App Integration**: Executes custom logic through Azure Function Apps.
- **Scalable and Reliable**: Designed to handle large volumes of data with high reliability.

## Prerequisites

Before you begin, ensure you have the following:

- An Azure subscription
- Access to Azure Portal
- Successful deployment of the MDTI API, the MDTI Content Hub Solution and the Function App located in this repo
- While technically you don't need Sentinel to deploy you would need it to run unless you decide to overhaul the project

## Getting Started

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMrSharpBones%2FMDTI%2Frefs%2Fheads%2Fmain%2FMDTI%2520Actor%2520Lookup%2FLogic%2520App%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>


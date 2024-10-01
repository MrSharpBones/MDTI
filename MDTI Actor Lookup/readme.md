# MDTI Actor Lookup

Welcome to the **MDTI Actor Lookup** project! This repository focuses on using the MDTI API, a function app, and a logic app together to automate Threat Infrastructure Chaining.

## Table of Contents

1. Introduction
2. Features
3. Getting Started
4. Deployment
5. Usage
6. Contributing
7. License

## Introduction

The MDTI Actor Lookup project leverages the MDTI API, a function app, and a logic app to automate the process of Threat Infrastructure Chaining. This automation helps in identifying and linking threat actors and their infrastructure efficiently.

## Features

- **Automated Threat Infrastructure Chaining**: Streamlines the process of identifying and linking threat actors.
- **Integration with MDTI API**: Utilizes the MDTI API for data retrieval and processing.
- **Azure Deployment**: Easily deployable to Azure for seamless integration and operation.

## Getting Started

To get started with the MDTI Actor Lookup project, you'll need to have an Azure account and the necessary permissions to deploy resources.  Also this playbook will use Copilot for Security to provide threat actor summaries, so you'll need to have at least 1 SCU configured in your tenant.  The MDTI API is a licensed feature, if you do not have the license please reach out to your account representative for purchase info and/or trial assistance.

You can however just use the MDTI API and the function app and hook them into whichever system you'd like.  You'll lose the SOAR functionality but you'll stil get the benefit of lightning fast infra chaining.

## Deployment

Follow these steps to deploy the application to Azure:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MrSharpBones/mdti-actor-lookup.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd mdti-actor-lookup
    ```
3. **Deploy to Azure**:
    - Use the Azure portal or Azure CLI to deploy the function app and logic app.
    - Assign the necessary names and configurations as per your requirements.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/MrSharpBones/MDTI/refs/heads/main/MDTI%20Actor%20Lookup/deploy-to-azure.json)

## Usage

Once deployed, you can attach the playbook to any/all Sentinel playbooks, Copilot will only be invoked should an actor group show up on in the results.  The MDTI API allows for unlimited (but throttled) API queries, so you can use this as much as you want without the worry of overage fees.

## Contributing

We welcome contributions to the MDTI Actor Lookup project! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Happy coding! If you have any questions or need further assistance, feel free to reach out.


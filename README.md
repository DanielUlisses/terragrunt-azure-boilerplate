# Terragrunt Azure Boilerplate
This repository serves as a comprehensive template integrating Terratest, Terragrunt, and Terraform within a GitHub Actions pipeline. Specifically tailored for deploying Azure infrastructure, the implementation leverages the power of DevContainers to streamline development and testing workflows.

# Getting Started

## 0. Fork this repository


Follow these steps to quickly get started with this repository:

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
```

Replace `your-username` and `your-repository` with your GitHub username and the name of the repository.

## 2. Open the Repository in VSCode

Navigate to the cloned repository using the following command:

```bash
cd your-repository
```

Launch Visual Studio Code:

```bash
code .
```

This assumes that you have Visual Studio Code installed. If not, you can download it [here](https://code.visualstudio.com/download).

## 3. Use DevContainer

Once the repository is open in VSCode, use the "Reopen in Container" feature to leverage the predefined development environment:

- Look for the green icon at the bottom right corner of the VSCode window.
- To open the command palette on Linux, press `Ctrl + Shift + P`.
- On macOS, press `Cmd + Shift + P`.
- Search for "Reopen in Container" and select the corresponding option.

This will set up a development container with the following tools:

- Terraform
- Terragrunt
- Terraform-docs
- Golang
- Python
- Pre-commit
- GitHub CLI
- Azure CLI

This environment is configured for a seamless development and testing experience.

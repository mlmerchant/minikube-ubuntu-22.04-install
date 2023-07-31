# Kubernetes Development Environment Setup / Minikube

This repository contains a bash script that automates the setup of a development environment with Kubernetes and associated tools. 

The script includes the installation of:
- `curl`: A tool to transfer data from or to a server.
- `kubectl`: A command-line tool for controlling Kubernetes clusters.
- `Docker`: An open-source platform to build, deploy, and manage containers.
- `cri-dockerd`: Container Runtime Interface for Docker, an implementation of the Kubernetes Container Runtime Interface (CRI).
- `conntrack`: A userspace command line program that allows a system administrator to manipulate the IP connection tracking system of the Linux kernel.
- `crictl`: A command-line interface for CRI-compatible container runtimes.
- `Minikube`: A tool that lets you run Kubernetes locally.

## Getting Started

### Prerequisites
- You need to have superuser (root) access to your system to run this script.
- Make sure you have `bash` installed on your system. 

### Installation
To setup your Kubernetes development environment, clone this repository to your local machine. Navigate to the directory and run the bash script using the following commands:

```bash
git clone https://github.com/mlmerchant/minikube-ubuntu-22.04-install.git
cd minikube-ubuntu-22.04-install
chmod +x install_minikube_ubuntu-22.04.sh
./install_minikube_ubuntu-22.04.sh
```

After successful execution, the script will have installed the aforementioned tools and started the Minikube service.

## Usage
After the successful execution of the script, you can now manage your Kubernetes cluster using the `kubectl` and `minikube` commands, run and manage containers with Docker and cri-dockerd, and monitor IP connections using `conntrack`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the terms of the MIT license. For more information, please refer to the LICENSE file.

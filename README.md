# 🚀 Vagrant Environments

A collection of ready-to-use **Vagrant configurations** for quickly deploying local virtual machines for development, testing, and Kubernetes labs.

---

## 📦 Available Environments

### ☸️ `k8s`

Create the required **master** and **worker nodes** with:

* 🌐 Additional network interface
* 💻 Configurable compute resources (CPU / RAM)
* 🔑 Automatic injection of the user's SSH public key

Perfect for building and testing a local Kubernetes cluster.

---

### 🐧 `ubuntu`

A simple **Ubuntu virtual machine** for testing purposes.

Includes:

* 🔑 User SSH public key setup
* ⚡ Fast and lightweight deployment

Ideal for quick experiments and sandbox environments.

---

### 🖥️ `ubuntuMultiple`

Create the required number of **Ubuntu virtual machines** with:

* 🔢 Configurable VM count
* 💻 Adjustable compute resources
* 🔑 User SSH public key injection

Useful for multi-node testing, networking labs, and distributed setups.

---

## ✨ Features

* Easy local environment provisioning
* Reusable infrastructure templates
* GitHub-friendly Markdown formatting
* Clean and readable structure

---

## 🛠️ Usage

```bash
vagrant up
```

To destroy the environment:

```bash
vagrant destroy -f
```

---

> Built for fast local development and testing with Vagrant.

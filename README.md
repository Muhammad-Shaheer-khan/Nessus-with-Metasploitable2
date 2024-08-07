# Vulnerability Management with Nessus 🔒🐧

Welcome to the repository for "Vulnerability Management with Nessus". This repository contains a PDF guide with step-by-step instructions on setting up and using Nessus for vulnerability management.

## Overview 📝

This guide covers:
- Setting up a vulnerable machine using Metasploitable2 💻
- Installing Nessus on Kali Linux 🐉
- Configuring Nessus for vulnerability scanning ⚙️
- Performing a basic network scan 🌐
- Analyzing scan results 🔍
- Generating vulnerability reports 📊

## Linux Commands 🐧💻

Here are some of the Linux commands you'll use:

### Installing Nessus 📦
```bash
sudo dpkg -i Nessus-10.8.1-debian10_amd64.deb
```
### Starting Nessus 🚀
```bash
systemctl start nessusd
```
### Accessing Nessus 🌐
Open your web browser and navigate to:
```bash
https://<System_IP>:8834/
```

## Detailed Guide 📘

For a detailed understanding with screenshots, download the PDF guide:
[Vulnerability Management with Nessus.pdf](https://github.com/Nessus-with-Metasploitable2/Vulnerability-Management-with-Nessus.pdf)

You can also read the full blog post for an in-depth guide and workflow:
[Vulnerability Management with Nessus: A Step-by-Step Guide](https://medium.com/@shaheerk2233/vulnerability-management-with-nessus-a-step-by-step-guide-cd321bde018a)

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

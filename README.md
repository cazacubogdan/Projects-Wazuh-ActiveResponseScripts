# Wazuh Active Response Script

This repository contains an active response script for Wazuh designed to address detected vulnerabilities. 
These scripts is intended to automate the response process when the vulnerability is detected.

## Author

- Author: [Bogdan Cazacu](https://github.com/cazacubogdan/)
- Email: contact@cazacubogdan.com

## Repository Information

- GitHub Repository: [https://github.com/cazacubogdan/Projects-Wazuh-ActiveResponseScripts](https://github.com/cazacubogdan/Projects-Wazuh-ActiveResponseScripts)

## Description

The scripts is triggered by Wazuh when a vulnerability is detected. It performs, in general, the following actions:

1. Checks for the presence of the vulnerability.
2. If the vulnerability is detected, it executes a series of steps to address the issue on the affected system(s).
3. Notifies the security team via email about the vulnerability detection.

## Note

Check each script you wish to use to see exactly what is does and how.

## Usage

To use these scripts, follow these steps:

1. Clone this repository to your Wazuh manager or agent machine.

```bash
git clone https://github.com/cazacubogdan/Projects-Wazuh-ActiveResponseScripts.git

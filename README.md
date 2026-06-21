# DevOps Linux Automation (KijaniKiosk)

## Overview

This project demonstrates Linux administration and DevOps fundamentals through automated provisioning and hardening of a simulated application environment.

The solution uses Bash scripting to configure users, groups, permissions, ACLs, systemd services, firewall rules, logging, monitoring, and verification controls while maintaining idempotent behavior.

## Features

* Package installation and validation
* Service account creation
* Group management
* Directory structure creation
* Linux permissions and ACLs
* systemd service deployment
* UFW firewall configuration
* Journal persistence
* Log rotation
* Health monitoring
* Automated verification
* Idempotent provisioning

## Technologies Used

* Ubuntu Linux
* Bash
* systemd
* ACL
* UFW
* Logrotate

## Project Structure

```text
.
├── kijanikiosk-provision.sh
├── access-model-final.md
├── hardening-decisions.md
├── integration-notes.md
├── kk-payments-hardening.md
├── post-remediation-verification.txt
├── pre-provisioning-audit.txt
├── provision-run-clean.log
├── provision-run-dirty.log
└── reflection.md
```

## Key DevOps Concepts

* Infrastructure Provisioning
* Linux Hardening
* Least Privilege Access
* Idempotency
* Monitoring and Verification
* Service Management
* Automation

## Future Improvements

* Convert Bash automation to Ansible
* Containerize services with Docker
* Add CI/CD using GitHub Actions
* Add monitoring with Prometheus
* Provision infrastructure using Terraform

# Git & GitHub Setup Guide

A complete, step-by-step guide to configuring Git on your machine, connecting your projects to GitHub, and managing your daily development workflow.

---

## 1. First-Time Git Setup
Perform these steps **once** on any new computer to install and configure your global Git settings.

### Step A: Install Git
* Download and install Git for your operating system: [Download Git for Windows](https://git-scm.com/install/windows)

### Step B: Configure Your Identity
Open **Git Bash** (or your preferred terminal) and run the following commands to clear any old configurations and set up your active GitHub account:

```bash
# Clear existing configurations (Optional)
git config --global --unset user.name
git config --global --unset user.email

# Set your GitHub identity
git config --global user.name "jaydevsatiya"
git config --global user.email "jaydevsatiya39@gmail.com"

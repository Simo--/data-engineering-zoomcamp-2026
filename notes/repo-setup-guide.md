# Repository Setup Guide

## 1. Create GitHub Repository
GitHub.com → New repository

Choose name, visibility, etc.


## 2. SSH Key Setup
SSH keys provide secure authentication without using passwords. They allow you to push/pull code securely.

Follow GitHub's official guides:

- [Generating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key)
- [Adding a new SSH key to your account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account)

**Notes**
- Use ed25519 keys (modern, secure)

- Passphrase is optional

- SSH key works for ALL your repositories once added

## 3. Clone & Setup
```bash
git clone git@github.com:username/repo-name.git
cd repo-name
# Type 'yes' when prompted about host authenticity
```

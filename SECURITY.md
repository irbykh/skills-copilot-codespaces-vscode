# Security Policy

## Supported Versions

This repository contains educational materials for GitHub Skills and GitHub Copilot. Security updates are applied to the latest version.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |

## Security Measures Implemented

### GitHub Actions Security
- All GitHub Actions are pinned to specific SHA commits to prevent supply chain attacks
- Workflow permissions follow the principle of least privilege
- Dependabot is configured for weekly security updates

### Action Versions
- `actions/checkout@08eba0b27e820071cde6df949e0beb9ba4906955` (v4)
- `skills/action-update-step@9046776751ec172f2b10c6b9569c108ffa701a2d` (v2)
- `skills/action-check-file@4d0de7b50a7e5cf7c041746656ebb03f2b54acaf` (v1)

## Reporting a Vulnerability

If you discover a security vulnerability in this repository, please report it by:

1. Creating a private security advisory on GitHub
2. Or emailing the repository maintainer directly

Please do not create public issues for security vulnerabilities.

### What to Include

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Suggested fixes (if any)

We will respond to security reports within 48 hours and work to address valid security concerns promptly.
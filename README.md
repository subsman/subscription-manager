# 📦 SubsMan: Subscription-Manager repository

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Latest version](https://img.shields.io/badge/Latest%20Release-v1.29.45-green)
![Supported Platforms](https://img.shields.io/badge/Platforms-RHEL%209%20|%20Oracle%20Linux%209%20|%20AlmaLinux%209%20|%20Rocky%20Linux%209-blue)

Subscription-Manager is part of collection of tools from Candlepin which allow companies to manage software subscriptions. 
The subscriptions allow users to access provided content over secure connections.

It works in any RHEL 9 based distro. Support for more, comming soon.

## 🚀 Easy install

### Repository setup:
```bash
sudo rpm --import https://subsman.github.io/RPM-GPG-KEY && \
sudo dnf install https://subsman.github.io/el9/subsman-release.rpm

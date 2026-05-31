# Ubuntu SSH Remote Access Lab

## Overview

This project demonstrates the setup of secure remote administration between a Windows host and an Ubuntu Server virtual machine using SSH.

## Objectives

- Install Ubuntu Server
- Configure SSH service
- Establish remote connectivity
- Implement SSH key authentication
- Practice Linux administration

## Technologies Used

- Ubuntu Server
- VirtualBox
- Windows PowerShell
- SSH

## Implementation

### 1. Verify SSH Service

```bash
sudo systemctl status ssh
```

### Screenshot

![SSH Service](screenshots/ssh-service-status.png)

### 2. Generate SSH Keys

```powershell
ssh-keygen
```

### 3. Configure Authorized Keys

```bash
nano ~/.ssh/authorized_keys
```

### Screenshot

![Authorized Keys](screenshots/authorized-keys.png)

### 4. Test SSH Connection

```powershell
ssh username@server-ip
```

### Screenshot

![SSH Login](screenshots/ssh-login-success.png)

## Skills Demonstrated

- Linux Administration
- SSH Configuration
- Networking
- Virtualization
- Cybersecurity Fundamentals
- Troubleshooting

## Outcome

Successfully configured secure remote access from a Windows system to an Ubuntu Server VM using SSH key-based authentication.

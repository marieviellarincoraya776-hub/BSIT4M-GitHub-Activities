# Laboratory 02 – Build the Cloud Infrastructure Blueprint
# Cloud Infrastructure Laboratory

## Mission Overview

This laboratory activity focused on exploring a Linux environment and understanding the basic components of cloud infrastructure. The activities involved investigating system information, identifying infrastructure components, comparing major cloud providers, and designing a simple cloud architecture.

## Objectives

- Identify the operating system and basic system resources in a Linux environment.
- Examine compute, storage, networking, and operating system components.
- Compare equivalent infrastructure services offered by AWS, Microsoft Azure, and Google Cloud Platform.
- Design a simple cloud infrastructure diagram.
- Practice basic Linux commands and technical documentation using Markdown.

## Cloud Infrastructure Components

### Compute Resources

The Linux environment provided a virtual CPU and memory resources. The environment had an Intel Xeon processor, one CPU core, and approximately 1.9 GiB of RAM.

### Storage Resources

The Linux environment used a virtual disk with an ext4 filesystem. The root filesystem had approximately 19 GB of storage capacity.

### Networking Resources

The environment provided virtual network interfaces and IP addresses. The observed IP addresses included `172.30.1.2` and `172.17.0.1`.

### Operating System

The laboratory environment used Ubuntu 24.04.4 LTS with Linux kernel version `6.8.0-136-generic`.

## Tools Used

- KillerCoda Linux Playground
- Ubuntu 24.04
- Linux Terminal
- Bash
- Nano text editor
- Python 3
- Pillow
- Markdown
- Microsoft PowerPoint

## Linux Commands Executed

```bash
whoami
groups
cat /etc/os-release
uname -r
lscpu
nproc
free -h
df -h /
mount
hostname
hostname -I
ls
ls -l
pwd
mkdir
nano
cat
python3

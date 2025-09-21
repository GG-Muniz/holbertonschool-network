basics_1

## Overview
This folder contains networking scripts for host resolution overrides, IPv4 address display, and a simple TCP listener for debugging.

## Contents
- 0-change_your_home_IP: Configure `/etc/hosts` to map localhost->127.0.0.2 and facebook.com->8.8.8.8
- 1-show_attached_IPs: Display all active IPv4 addresses
- 2-port_listening_on_localhost: Listen on TCP port 98 at 127.0.0.1 and echo input

## Requirements
- Ubuntu 22.04
- Scripts executable, pass shellcheck 0.7.0
- Shebang: `#!/usr/bin/env bash`
- Second line: comment explaining the script purpose

## Usage
- Change host mappings (requires sudo):
```bash
sudo ./0-change_your_home_IP
```
- Show active IPv4 addresses:
```bash
./1-show_attached_IPs | cat -e
```
- Listen on port 98 on localhost (requires sudo on some systems):
```bash
sudo ./2-port_listening_on_localhost
```

holbertonschool-network

## Project overview
This repository contains "basics_0" networking tasks. It includes short answer files and two Bash scripts to inspect listening ports and test host reachability. The work targets Ubuntu 22.04 and follows Holberton School requirements.

## Requirements
- Ubuntu 22.04
- All Bash scripts are executable
- Shebang must be exactly: `#!/usr/bin/env bash`
- Second line in each script explains what the script does
- Scripts pass shellcheck without errors

## Directory structure
- basics_0/0-OSI_model: Answers about the OSI model
- basics_0/1-types_of_network: Answers about types of networks
- basics_0/2-MAC_and_IP_address: Answers about MAC and IP addresses
- basics_0/3-UDP_and_TCP: Answers about UDP and TCP
- basics_0/4-TCP_and_UDP_ports: Display listening TCP/UDP ports with PID/program
- basics_0/5-is_the_host_on_the_network: Ping a provided IP address 5 times

## Usage
- Display listening ports (requires privileges on some systems):
```bash
sudo ./basics_0/4-TCP_and_UDP_ports
```
- Ping an IP address 5 times (prints usage if no argument is provided):
```bash
./basics_0/5-is_the_host_on_the_network 8.8.8.8
```

## Notes
- Answer files contain only the number of the correct choice per line.

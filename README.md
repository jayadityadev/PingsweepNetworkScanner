# Ping Sweep Network Scanner

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgement](#acknowledgement)

## Overview

This Python script allows you to perform a ping sweep on a range of IP addresses within a specified subnet to identify live hosts. It supports both Windows and Unix-like systems for the ping command.

## Features

- Scan a range of IP addresses within a subnet.
- Detect live hosts within the specified range.
- Cross-platform compatibility (Windows and Unix-like systems).

## Getting Started

#### Clone this repository to your local machine:

```bash
git clone https://github.com/jayadityadev/PingsweepNetworkScanner.git
```

## Usage

1. Run the program

   ```bash
   python main.py
   ```

2. Follow the on-screen instructions to provide the following information:

   * Subnet IP (e.g., 192.168.0)
   * Starting IP range
   * Ending IP range

### Example

```python
Enter the SUBNET IP: 192.168.1
Enter Starting Range: 1
Enter Ending Range: 10
```
The script will scan the hosts ranging from IP Address: 192.168.1.1 to 192.168.1.10.

```bash
Scanning completed in 0:00:13.741418

Live Hosts:
192.168.1.1 --> Live
192.168.1.2 --> Live
192.168.1.5 --> Live
192.168.1.7 --> Live
192.168.1.9 --> Live
```
## Contributing

Contributions are welcome! If you would like to improve this program, please follow these steps:

1. Fork the repository.
   
2. Create a new branch for your feature or bugfix:
   
   ```bash
   git checkout -b new-feature.
   ```
   
3. Make your changes and commit them (ensure they are well documented):
   
    ```bash
    git commit -m 'Add new feature'.
   ```
    
4. Push to the branch:
   
    ```bash
    git push origin new-feature
   ```
    
5. Create a pull request from your fork's branch to the main repository's main branch.

## Acknowledgement

Thank you for using Ping Sweep Network Scanner! If you have any feedback or suggestions, feel free to open an issue on this repository.

`The efficiency of the program solely depends on factors such as network traffic and connectivity of devices to the router/dhcp server. Also, in some cases, the program skips some live hosts, even though they're up due to delay in responding to the ping command within the time slot.`
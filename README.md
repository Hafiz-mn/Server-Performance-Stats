# Server-Performance-Stats

# Linux Health Check

A simple Bash script that provides a quick overview of a Linux system's health.

## Features

- Displays operating system information
- Shows kernel version and architecture
- Displays CPU information
- Shows memory usage
- Displays disk usage
- Lists top CPU-consuming processes
- Lists top memory-consuming processes

## Output

The script displays:

- System Information
- CPU Details
- Memory Usage
- Disk Usage
- Top Processes by CPU
- Top Processes by Memory

## Requirements

- Linux
- Bash
- Standard Linux utilities:
  - hostnamectl
  - lscpu
  - free
  - df
  - ps
  - grep

These utilities are available by default on most Linux distributions.

## Installation

Clone the repository:
git clone https://github.com/Hafiz-mn/Server-Performance-Stats.git

```bash


Go to the project directory:

```bash
cd linux-health-check
```

Make the script executable:

```bash
chmod +x health
```

Run the script:

```bash
./health
```

## Optional: Run as a Command

Copy the script to a directory in your PATH:

```bash
mkdir -p ~/.local/bin
cp health ~/.local/bin/
chmod +x ~/.local/bin/health
```

Ensure `~/.local/bin` is included in your PATH.

Then simply run:

```bash
health
```

## Example

```text
== System ==
Operating System: Ubuntu 24.04 LTS
Kernel: Linux 6.8.0
Architecture: x86-64

== CPU ==
Model name: AMD Ryzen 7 5800H
CPU(s): 16
Thread(s) per core: 2
Core(s) per socket: 8

== MEM ==
...

== DISK USAGE ==
...

== TOP PROCESSES BY CPU ==
...

== TOP PROCESSES BY MEM ==
...
```



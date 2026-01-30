# Linux Process Management

## Overview
A process is a running instance of a program.
Understanding processes is important for monitoring system performance and detecting suspicious activity.

## Important Concepts
- **PID (Process ID)**: unique ID for each process
- **Foreground process**: runs directly in the terminal
- **Background process**: runs without blocking the terminal

## Common Commands
- `ps` : show current running processes
- `ps aux` : show all processes with details
- `top` : real-time process monitoring
- `htop` : enhanced version of top (if installed)
- `kill` : terminate a process by PID
- `kill -9` : force stop a process

## Example Usage
- `ps aux | grep ssh`
  - Find SSH-related processes
- `top`
  - Monitor CPU and memory usage in real time

## Security Perspective
- Unexpected processes may indicate malware
- High CPU usage could signal a compromised system
- Process monitoring is part of SOC daily activities

## Notes
Process analysis helps identify abnormal behavior in a Linux system.

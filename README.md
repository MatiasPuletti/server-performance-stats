# Server Performance Stats Report

This script generates a report on server performance and provides essential statistics, including CPU usage, memory usage, disk usage, OS version, uptime, and more. It is useful for quickly assessing the current health and load on a Linux server.

> **Note:** Inspired by the [Server Stats Project on roadmap.sh](https://roadmap.sh/projects/server-stats).

## Features

- **OS Version**: Displays the current OS name and version.
- **Uptime**: Shows how long the server has been running.
- **Load Average**: Provides the load average for the past 1, 5, and 15 minutes.
- **Logged-in Users**: Lists the count of logged-in users.
- **Failed Login Attempts**: Counts and displays the number of failed login attempts.
- **CPU Usage**: Shows total CPU utilization.
- **Memory Usage**: Displays used and free memory in MB.
- **Disk Usage**: Shows disk usage with free and used space.
- **Top Processes**:
  - **Top 5 by CPU Usage**: Lists the top 5 processes consuming the most CPU.
  - **Top 5 by Memory Usage**: Lists the top 5 processes consuming the most memory.

## Usage

1. **Make the script executable**:  
   Run the following command to make the script executable:
   ```bash
   chmod +x script_name.sh
   ```

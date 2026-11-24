# Server Performance Stats

A Bash script that analyzes basic Linux server performance statistics and provides a quick health overview of the system.

## Project URL

https://roadmap.sh/projects/server-stats

## Features

- Total CPU Usage
- Total Memory Usage
- Memory Usage Percentage
- Total Disk Usage
- Disk Usage Percentage
- Top 5 Processes by CPU Usage
- Top 5 Processes by Memory Usage
- System Uptime
- Load Average
- Logged-in Users
- OS Information
- Recent Failed Login Attempts

## Technologies Used

- Bash Shell Scripting
- Linux System Commands

## Commands Used

| Command | Purpose |
|----------|----------|
| top | CPU statistics |
| free | Memory statistics |
| df | Disk utilization |
| ps | Process information |
| uptime | Uptime and load average |
| who | Logged-in users |
| grep | Filter output |
| awk | Extract specific fields |
| head | Display top records |
| tail | Display recent records |

## How to Run

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/server-performance-stats.git
```

### Navigate to the Project Directory

```bash
cd server-performance-stats
```

### Make the Script Executable

```bash
chmod +x server-stats.sh
```

### Run the Script

```bash
./server-stats.sh
```

## Sample Output

```text
=====================================================
               SERVER PERFORMANCE STATS
=====================================================

CPU Usage
--------------------------------------
Total CPU Usage : 25%

Memory Usage
--------------------------------------
Total Memory : 3950 MB
Used Memory  : 2200 MB
Free Memory  : 1750 MB
Usage        : 55.70%

Disk Usage
--------------------------------------
Total Disk  : 20G
Used Disk   : 15G
Free Disk   : 5G
Usage       : 75%

Top 5 Processes by CPU Usage
Top 5 Processes by Memory Usage

System Uptime
Load Average
Logged-in Users
OS Information
Recent Failed Login Attempts
```

## Learning Outcomes

Through this project, I learned:

- Bash scripting fundamentals
- Linux system administration basics
- Monitoring CPU, memory, and disk utilization
- Process management
- Server troubleshooting techniques
- Working with Linux commands such as `top`, `free`, `df`, and `ps`

## Author

Sumit

#  System Performance Monitoring with Python, SQL Server & Power BI

![alt_text](https://github.com/bacdillon/PowerBI/blob/main/Power%20BI%20System%20Performance.jpg)

A Python-based system monitoring application that captures real-time performance metrics using the psutil library. The application continuously logs key system data into a SQL Server database every second, enabling detailed analysis and visualization in Power BI.

# Key Metrics Collected:
Metric Type	Description
CPU Usage	% utilization of CPU
CPU Calls & Interrupts	System-level CPU calls and interruptions
Memory Usage	% usage, memory free, memory used
Disk Usage	% disk space used
Network	Bytes sent and received

# Key Features:
Real-time data capture loop using psutil.
Data is written to a SQL Server database for persistence.
Power BI dashboard connects to the database (or an exported CSV) to visualize system health:
Gauge visuals for CPU, disk, and memory usage.
Time-series charts for network and CPU activity.
Donut chart for memory distribution (free vs used).



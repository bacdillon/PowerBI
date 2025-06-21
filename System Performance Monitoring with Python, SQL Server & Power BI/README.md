#  System Performance Monitoring with Python, SQL Server & Power BI

![alt_text](https://github.com/bacdillon/PowerBI/blob/main/System%20Performance%20Monitoring%20with%20Python%2C%20SQL%20Server%20%26%20Power%20BI/Power%20BI%20System%20Performance.jpg)

A Python-based system monitoring application that captures real-time performance metrics using the psutil library. The application continuously logs key system data into a SQL Server database every second, enabling detailed analysis and visualization in Power BI.

### Key Metrics Collected:
- CPU Usage	% utilization of CPU
- CPU Calls & Interrupts	System-level CPU calls and interruptions
- Memory Usage	% usage, memory free, memory used
- Disk Usage	% disk space used
- Network	Bytes sent and received

### Key Features:
- Real-time data capture loop using psutil.
- Data is written to a SQL Server database for persistence.
- Power BI dashboard connects to the database (or an exported CSV) to visualize system health:<BR>
 -- Gauge visuals for CPU, disk, and memory usage.<BR>
 -- Time-series charts for network and CPU activity.<BR>
 -- Donut chart for memory distribution (free vs used).<BR>



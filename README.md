###########################

GetCPUandMemoryUsageOfProcessByPID_ReubenPython3Class

Class that monitors CPU and memory usage for a process PID.

Reuben Brewer, Ph.D.

reuben.brewer@gmail.com

www.reubotics.com

Apache 2 License

Software Revision B, 12/22/2025

Verified working on:

Python 3.11/12/13.

Windows 10, 11 64-bit

NOTE:
The result is:
CPU usage as a percentage of one full logical core per 100%
So if you have a 4-core CPU with hyperthreading (i.e. 8 logical processors):
If your process uses 100% of 1 core, cpu_percent() will return ~12.5% (100 ÷ 8).
If your process is multi-threaded and fully uses 2 cores, it would show ~25%.
100% means it is using all available logical CPUs fully.

###########################

########################### Python module installation instructions, all OS's

GetCPUandMemoryUsageOfProcessByPID_ReubenPython3Class, ListOfModuleDependencies: ['psutil']

GetCPUandMemoryUsageOfProcessByPID_ReubenPython3Class, ListOfModuleDependencies_TestProgram: ['keyboard']

GetCPUandMemoryUsageOfProcessByPID_ReubenPython3Class, ListOfModuleDependencies_NestedLayers: []

GetCPUandMemoryUsageOfProcessByPID_ReubenPython3Class, ListOfModuleDependencies_All:['keyboard', 'psutil']

###########################

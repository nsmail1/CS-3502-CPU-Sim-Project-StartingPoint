# CS 3502 CPU Scheduling Simulator

## Author
**Nick Smail**

## Project Overview

This project extends the CPU Scheduling Simulator starter application by implementing two additional CPU scheduling algorithms:

- Shortest Remaining Time First (SRTF)
- Highest Response Ratio Next (HRRN)

The simulator allows users to compare multiple scheduling algorithms using the same workload while displaying detailed performance metrics such as waiting time, turnaround time, response time, CPU utilization, and throughput.

---

# Requirements

- Visual Studio 2022 Community (or later)
- .NET Framework supported by the starter project
- Windows operating system

---

# Building the Project

1. Download or clone the project repository.

2. Open the solution (`.sln`) file in Visual Studio.

3. Restore any required NuGet packages (Visual Studio normally does this automatically).

4. Select **Debug** or **Release** configuration.

5. Build the project using:

```
Build → Build Solution
```

or press:

```
Ctrl + Shift + B
```

6. Ensure the build completes successfully without errors.

---

# Running the Program

Run the application by pressing:

```
F5
```

or

```
Debug → Start Debugging
```

You may also run without the debugger using:

```
Ctrl + F5
```

---

# Using the Simulator

1. Launch the application.

2. Load or generate a workload.

3. Select one of the available scheduling algorithms:

- FCFS
- SJF
- Priority
- Round Robin
- SRTF
- HRRN

4. Run the simulation.

5. Review the scheduling metrics displayed on the Results page.

6. Optionally click **Export Results** to save the performance metrics as a CSV file.

---

# Features Added

Compared to the starter project, this version includes:

- Shortest Remaining Time First (SRTF)
- Highest Response Ratio Next (HRRN)
- Additional scheduling metrics
  - Average Waiting Time
  - Average Turnaround Time
  - Average Response Time
  - CPU Utilization
  - Throughput
  - Total Burst Time
  - Total Elapsed Time
- CSV export functionality
- Updated user interface with new scheduling buttons

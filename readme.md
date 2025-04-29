
## Building the Solution

1. Open `CpuSchedulingWinForms.sln` in Visual Studio.  
2. Restore NuGet packages if prompted.  
3. Build the solution (Ctrl+Shift+B).  

## Running the Application

1. Start without debugging (Ctrl+F5) or Debug → Start Debugging.  
2. In the main window, switch to the **CPU Scheduler** tab.  
3. Enter the **Number of Processes**.  
4. Click any algorithm button (e.g. FCFS, SRTF, MLFQ).  
5. Follow the input prompts for arrival time, burst time, (and priority for Priority scheduling).  
6. View per-process metrics and average results in pop-up dialogs.  

## Sample Workloads

Three example workloads are used in our report:

- **A**: Staggered arrivals (0–4) with varied bursts [3,5,12,20,4]  
- **B**: All arrive at 0 with identical bursts [5,5,5,5,5]  
- **C**: Interleaved arrivals (0–8) with mixed bursts [10,1,2,1,5]  

Use these to compare Average Waiting Time (AWT) and Average Turnaround Time (ATT).  

## Report

The LaTeX report `cpu_scheduling_report.tex` (and corresponding PDF) documents:

- Implementation details and code snippets  
- Test workloads, tables, and charts  
- Detailed algorithm descriptions and comparative analysis  
- Challenges and lessons learned  

## Video Demonstration

A 3–5 minute MP4 or YouTube link demonstrating:

- User interface walkthrough  
- Running each scheduling algorithm  
- Interpreting the results and insights  

## License

This project is released under the MIT License. Feel free to fork and extend.

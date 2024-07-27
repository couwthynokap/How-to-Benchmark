# DPC and ISR tracing with Xperf

- This guide will help you master the DPC (Deferred Procedure Call) and ISR (Interrupt Service Routine) tracing method using the “Windows Performance Toolkit”. It is a powerful tool for analyzing Windows system performance to identify bottlenecks related to interrupts and deferred procedures.

## Introduction:

> DPC (Deferred Procedure Call) and ISR (Interrupt Service Routine): These are special types of procedures that are used to handle interrupts and pending tasks. Sometimes they can cause performance problems, so profiling them is important for troubleshooting.
> Xperf: A tool for collecting and analyzing trace data in Windows. It is part of the “Windows Performance Toolkit”.

## Installation:

- Install “Windows Performance Toolkit” c guru3d from [mbk1969](https://forums.guru3d.com/threads/simple-way-to-trace-dpcs-and-isrs.423884/) or the version from [Calypto](https://github.com/Calypto/xperf-dpcisr-script).

```
Uncheck all items except “Windows Performance Toolkit” during installation. 
```

- Download the script that will automate the tracing process. The script will perform all the necessary steps. If you want to create new tests, delete all files from the C:\dpc folder.

# Usage:

- Run the script: Run the downloaded script. It will perform the following actions:
```
Will create a new Xperf trace session.
Will start recording trace data.
Will stop recording after a specified period of time.
Will save the trace data to an .etl file.
```

## Analyze the data:

```
Open the .etl file in “Windows Performance Analyzer” (WPA).
Use WPA to analyze the resulting data. Locate the sections related to DPC and ISR to examine their behavior. 
```

## Additional tips:

> Keep records: Back up the .etl files you receive so that you can return to them later.
> Use WPA: WPA provides many tools for analyzing trace data, including graphs, filters, hierarchical browsing, etc. 
> Be mindful of resources: Collecting trace data can require a significant amount of resources. Make sure you have enough disk space.

## Important:

> Study the Xperf and WPA documentation to learn more about the available options and settings.
> DPC and ISR tracing is a powerful tool, but it should be used with caution. Improper use can lead to system performance problems.

# PresentMon

> PresentMon: A tool for analyzing graphics performance in Windows. It is a free tool that allows you to analyze graphics performance in Windows by providing detailed information about the frame rendering process. It is ideal for game developers to optimize the performance of their games and identify bottlenecks.

## Installation

- Download and install PresentMon from [official website](https://github.com/GameTechDev/PresentMon/releases).

## Launch

- Launch PresentMon and click “Start Capture”.

## Customize

- Select the desired options

```
Enable vsync: Enable vertical synchronization (Vsync) if your application uses it.
Show timestamps: Enable the display of timestamps for more detailed analysis.
```

## Start the application

- Start the application you want to test and run your test.


## Stop Capture
- When your test is complete, click “Stop Capture” in PresentMon.

## Analyze Data: 

- PresentMon will show you a graph with information about:

```
FPS (frames per second): `` `` Frame rate.
Draw Time: The time taken to draw the frame.
Presentation Time: The time spent displaying the frame on the screen.
Wait Time: The time the application spends waiting for, for example, vertical synchronization.
```

## Advantages of PresentMon:

> Easy to use: PresentMon has a simple interface, making it accessible to a wide range of users.
> Detailed information: It provides detailed information about rendering time, presentation time and other important performance metrics.
> Graphical Interface: PresentMon provides graphs that allow you to visualize the time taken for each stage of the rendering process. 
> Free: PresentMon is a free tool that is available to everyone.

## PresentMon Limitations:

> Limited data: PresentMon only provides basic information about graphics performance. For more in-depth analysis, you may need to use other tools such as Xperf.
> Not suitable for complex scenarios: PresentMon may not be functional enough for some complex benchmarking scenarios. 

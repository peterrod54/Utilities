# Windows-_Based_ Utilities

The purpose of this project is to provide an assortment of Windows tools to assist in managing your environment. Below is a description of each utility.

## Software Inventory

### Description

This utility inventories installed software pertaining to your Windows domain environment (_default mode_). If no domain exists, then it runs in single-host mode.


## Windows Log Aggregator & Analyzer (_LogSpear_)

This tool introduces a cost effective approach to Windows Log Management.

### Description

There are between 700 and 800 event log-file types on any given Windows Server, _more depending upon installed applications and devices_. Yet, for many IT administrators, the focus is typically on only three log-file types: _Application, System_, and _Security_. 

When you consider the plethora of log-file types providing important information on the general health of your systems, it's evident that focusing on only _three_ is short-sighted. It is also evident that the notion of having a log management solution becomes more than just a _nice to have_.

The LogSpear utility is designed to pull _error, warning_ and _critical_ events, from every log file and output the results (as a well-formatted _Excel_ file) to the **_C:\temp\LogSpear_** folder.


### Getting Started

#### Dependencies

+ The **_LogSpear_** utility is _currently_ Windows-based (_LogSpear will not run on Linux or macOS_; however, future versions will support Linux)
+ The _GitHub_ iteration of LogSpear only works on a per-server basis (there is however an _Enterprise_ version)
+ Requires the Windows EXCEL application to view the output file

#### Installation and Execution Instructions

+ Download _LogSpear.exe_ 
+ When executing _LogSpear.exe_, you'll be prompted to enter the _hostname_ of the server that you want to collect the log files from, and the start time (in hours) where you want LogSpear to begin collecting events

###### **NOTE:** Obscure antivirus engines register a false-positive regarding the LogSpear utility. It's recommended that you use a browser other than Microsoft Edge for downloading.



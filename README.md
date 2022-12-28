#  Windows Log Aggregator & Analyzer (_LogSpear_)

This project introduces a cost effective approach to Windows Log Management

## Description

There are between 700 and 800 event log-file types on any given Windows Server, _more depending upon installed applications and devices_. Yet, for many IT administrators, the focus is typically on only three log-file types: _Application, System_, and _Security_. 

When you consider the plethora of log-file types providing important information on the general health of your systems, it's evident that focusing on only _three_ is short-sighted. It is also evident that the notion of having a log management solution becomes more than just a _nice to have_.

The LogSpear utility is designed to pull _error, warning_ and _critical_ events, from every log file and output the results (as a well-formatted _XLSX_ file) to the **_C:\temp\LogSpear_** folder.


## Getting Started

### Dependencies

+ The **_LogSpear_** utility is _currently_ Windows-based (_LogSpear will not run on Linux or macOS_; however, future versions will support Linux)
+ The _GitHub_ iteration of LogSpear only works on a per-server basis (there is however an _Enterprise_ version)

### Installation and Execution Instructions

+ Download _LogSpear.exe_ 
+ When executing _LogSpear.exe_, you'll be prompted to enter the hostname of the server that you want to collect the log files from, and the start time (in hours) where you want LogSpear to begin collecting events
+ Collecting the _Security_ logs requires elevated permissions (LogSpear will still collect log data without elevated permissions, but not the Security logs)

###### **NOTE:** Obscure antivirus engines register a false-positive regarding the LogSpear utility. It's recommended that you use a browser other than Microsoft Edge for downloading.


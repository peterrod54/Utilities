# Windows Log Aggregator & Analyzer (_LogSpear_)

This project introduces a cost effective approach to Windows log management, specifically targeting the _Small Medium-Sized Business_ **(SMB)** who, in general, have avoided pricey log management solutions, i.e. _Splunk_, _LogRythm_, et al. For the SMB, it's about getting the most bang for your buck; yet, there's no reason why the SMB can't get the same effective log management solution _for pennies on the dollar_.

## Description

There are between 700 and 800 log-file types on any given Windows Server, _more depending upon installed applications and devices_. Yet, for most IT administrators, the focus is on only three log files: _Application, System_, and _Security_. 

When you consider the plethera of log-file types that provide crucial information on the general health of your systems, it's evident that focusing on only those three log files is being a bit short-sighted. It's also evident that a log management solution becomes more than just a _nice to have_.

The LogSpear utility app is designed to pull _error, waring_ and _critical_ events, from every log file and output the results as a CSV file to the **_C:\temp_** folder.


## Getting Started

### Dependencies

+ The **_LogSpear_** utility app is exclusive to the Windows environment; it will not run on Linux or MacOS.

### Installation and Execution

+ Download the LogSpear utility and run it on the server that you want to collect the Windows logs. 
+ Follow the prompts that appear on the screen, in particular, enter the _start time_ (in hours) where you want LogSpear to begin collecting events
+ Consider running the app with elevated permissions if you expect to gather _Security_ logs (_which naturally you'll want to include in your log analysis_)

## What's Next

While the **_LogSpear_** utility is not (_in and of itself_) the log management solution alluded to, it is nevertheless its foundation. If you're interested in deploying an _enterprise-wide, cost-effective_ log management solution, then reach out to discuss this matter and arrange a demo: [Peter](mailto:peter@variacom.com)

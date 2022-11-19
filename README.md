# Windows Log Aggregator & Analyzer (_LogSpear_)

This project introduces a cost effective approach to Windows log management, specifically targeting the _Small Medium-Sized Business_ **(SMB)** who, in general, have avoided pricey log management solutions, i.e. _Splunk_, _LogRythm_, et al. For the SMB, it's about getting the most bang for your buck; yet, there's no reason why the SMB can't get the same effective log management solution _for pennies on the dollar_.

## Description

There are between 700 and 800 log-file types on any given Windows Server, _more depending upon installed applications and devices_. Yet, for most IT administrators, the focus is on only three log file types: _Application, System_, and _Security_. 

When you consider the plethora of log-file types that provide important information on the general health of your systems, it's evident that focusing on only three log file types is being a bit short-sighted. It's also evident that a log management solution becomes more than just a _nice to have_.

The LogSpear utility app is designed to pull _error, warning_ and _critical_ events, from every log file and output the results as a CSV file to the **_C:\temp_** folder.


## Getting Started

### Dependencies

+ The **_LogSpear_** utility only works in a Windows environment; it will not run on Linux or macOS.

### Installation and Execution

+ Download/install the 7-Zip file extraction software: [download site](https://www.7-zip.org/download.html)
+ Download and extract _LogSpear.7z_ from GitHub repository, and when prompted for password, enter: _qwerty_
+ Run _LogSpear.exe_ and enter the start time (in hours) where you want LogSpear to begin collecting events
+ If you expect to collect _Security_ logs, then you'll need to run the app with elevated permissions (LogSpear will still collect log data without elevated permissions, just not the Security logs)

###### **NOTE:** A couple of obscure antivirus engines have registered a false-positive regarding the LogSpear utility app.

## What's Next

While the **_LogSpear_** utility is not (_in and of itself_) the log management solution alluded to earlier, it is nevertheless at the core of its foundation. If you're interested in deploying an _enterprise-wide, cost-effective_ log management solution, we can arrange an in-depth discussion and demo: [Peter](mailto:peter@variacom.com)

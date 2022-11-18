# Windows Log Aggregator & Analyzer (_LogSpear_)

## Description
In addition to the _Application_, _Security_ and _System_ logs, there are between 700 and 800 log-file types on any given Windows Server; while some servers will contain more log-types depending on installed applications and hardware devices for that server.

The intention here is to introduce a cost effective approach to Windows log management, specifically focused on the **Small Medium-Sized Businesses** (SMB) who, in general, have avoided over-priced log management solutions, i.e. _Splunk_, _LogRythm_, et al.

While the log management solution that I have alluded to is beyond the scope of this project, due to the breadth and depth of its nature, provided instead is a utility app that saves time and bring you a step closer to managing your Windows log infrastructure.

## Getting Started
### Dependencies

+ The LogSpear utility app is exclusive to the Windows environment
+ You should consider running the app with elevated permissions if you expect to gather the _Security_ logs (**which naturally you'll want to include in your log analysis**)

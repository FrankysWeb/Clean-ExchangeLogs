# Clean-ExchangeLogs
 Clean Exchange Server Logfiles to free up disk space

## Usage
You have to edit the first lines of the script if you don't you the default paths:

```
# Cleanup logs older than the set of days in numbers
$Days = 14

# Path of the logs that you like to cleanup
$IISLogPath = "C:\inetpub\logs\LogFiles\"
$ExchangeLoggingPath = "C:\Program Files\Microsoft\Exchange Server\V15\Logging\"
$ETLLoggingPath = "C:\Program Files\Microsoft\Exchange Server\V15\Bin\Search\Ceres\Diagnostics\ETLTraces\"
$ETLLoggingPath2 = "C:\Program Files\Microsoft\Exchange Server\V15\Bin\Search\Ceres\Diagnostics\Logs\"
$UnifiedContentPath = "C:\Program Files\Microsoft\Exchange Server\V15\TransportRoles\data\Temp\UnifiedContent"
```

Download and copy this script to an Excchange Server.
Run this script:

```
.\Clean-ExchangeLogs.ps1
```

## Special Thanks!
This script was first published on [Ali Tajran Website](https://www.alitajran.com/cleanup-logs-exchange-2013-2016-2019/),
I modified Ali's script to cover Exchange Unfified Content Directory and add some stats to the output.

## Tested Exchange / Windows Server Versions

 - Exchange Server 2016
 - Exchange Server 2019

 - Windows Server 2016
 - Windows Server 2019

## Website
 [FrankysWeb](https://www.frankysweb.de/)

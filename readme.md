This play book quarantines and autoscales the azure vm where malware is found.

The following actions should be taken before this Logic App can be deployed:

- Trend Micro Cloud One - Workload Security - Account(https://cloudone.trendmicro.com/docs/jp/workload-security/free-trial/)

- Azure Scale Set with an image of the vm with the Deep security agent installed(https://cloudone.trendmicro.com/docs/jp/workload-security/azure-vmss/)

- Syslog server that receives events from the Deep security agent and forwards them to Sentinel(https://cloudone.trendmicro.com/docs/jp/workload-security/event-syslog/)

- Create Automation Account (https://docs.microsoft.com/en-us/azure/automation/automation-quickstart-create-account)
# Progress Report

## Agenda
- Progress in this 2 weeks and before 2 weeks
- Problems and Questions
- My assignments
## What I have done more than 2 weeks ago and assignment in this 2 weeks
### What I have done
1. I want to use STARDUST to observe what cyber crimers do in Internet environment ->
2. I need to know what cyber attackers can do and how I can observe that ->
3. I used WireShark and Sysmon. 
    - Sysmon is a tool related to event logs.
    - In a STARDUST workshop, it was used to analyze malware behavior,but when observing cyber-attacks on companies,
    - I may need to find other services because some types of logs may not be captured by sysmon alone.
4. I found 6 services that can replace sysmon↓↓
![](20241204_PR6.png)
6 services have different advantages, but these information are not reliable because I found them by using ChatGPT.
I need to brush up this table.

### What I did
1. Think how to improve this table. I got advices that I should focus on logs that I can get and price.

    - About logs
      - Back bround
        - **What logs are** thought to be **related to cyber attacks against companies?**
         - I found interesting paper
            - National Security Agency provide a table of all the event codes that they find interesting for detecting baddies in windows network.(Windows 7,8 and this article was published 10 years before)
             - I couldn't find this type of paper written recently
            - Some articles show some logs, but not all logs are not same.
        - What logs are related to cyber attacks -> Overview is known, but details are not known...
      - I had to gather logs from STARDUST.
        - ffri yarai is used to get client log, but it is not good for honeypot.
      - I installed a service to send event log to syslog, and the amount of data was 743kB in 16minutes. -> STARDUST's event log per day may be 3GB(I will check later.)
    - About prices
      - Some services depends on the amount of data of logs per day or month
        - Maximum amount of Client Logs per an hour (no cyber attack)-> 20MB.
          - Client logs are gathered by using yarai agent. <-Extraction of logs determined to be suspicious
        - When we can use services (per day -> 5GB per month -> 150GB), we will have no 
    problems about log volume...? -> I changed contracts not suitable due to data volume to red color
![](20241204_red.png)
3. 
    - Some services are not available.
    - Our observing environment's scale is too small to use Splunk ...?
4. aa

## Problems and Questions
- Is my method of measuring the amount of data collect ?
## What I will do in this week

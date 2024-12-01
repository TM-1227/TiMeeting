# Progress Report

## Contents
- What I did in this 2 weeks and before 2 weeks
- Problems and Questions
- My assignments
## What I have done more than 2 weeks ago and assignment in this 2 weeks
### What I have done
1. I want to use STARDUST to observe what cyber crimers do in company Internet environment ->
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
      - **What logs are** thought to be **related to cyber attacks against companies?**
        - I found interesting paper
          - National Security Agency provide a table of all the event codes that they find interesting for detecting baddies in windows network.(Windows 7,8 and this article was published 10 years before)
          - I couldn't find this type of paper written recently
        - Some articles show some logs, but not all logs are not same.
      - What logs are relaated to cyber attacks -> Overview is known, but details are not known...
    - About prices
      - Some services depends on the amount of data of logs per day or month
        - Maximum amount of Client Logs per an hour (no cyber attack)-> 20MB.
        - When we can use services (per day -> 1GB per month -> 30GB), we will have no 
problems of log volume...?
      - Functions that must be needed
        - Analyze what logs are different significantly between normal and abnormal conditions. -> To know logs that indicate cyber attack...
## Problems and Questions

## What I will do in this week

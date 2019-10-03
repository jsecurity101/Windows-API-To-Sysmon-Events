# API to Sysmon-EventIDs
A repository that maps API calls to Sysmon Event ID's. 

## API Mapping Google Sheet: 
[API Data Relationships](https://docs.google.com/spreadsheets/d/1T4sm1freM4KJk9Wu8GNxDQDRPur7159kcUji9pk03xU/edit?usp=sharing)


## API Mapping Images:
These images can be found in within the `API-Mapping-Images` directory. 


### Research Notes:
- API(A) - API accepts ASCII character strings. API(W) - api accepts wide character strings. 
- Nt(API) - User mode. Zw(API) called from kernel. If Nt(API) Zw is implied.
- API's listed are ones that were seen within the stack during a breakpoint of the event registration mechanism.

## Comments:
### Credit:
A big thanks and credit goes out to the following individuals for the help and insight they had on this project:

Matt Graeber - Guiding me through the Reverse Engineering, with walking me through muliple function calls, and verifying many of these call back functions. 
Brian Reitz - Helping me understand function calls and interprocess communication.
Jared Atkinson - Helping me understand function calls and interprocess communication. 

### Resources:
https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/what-does-the-zw-prefix-mean-
https://specterops.io/assets/resources/Subverting_Sysmon.pdf
https://blog.xpnsec.com/evading-sysmon-dns-monitoring/
https://github.com/hunters-forge/OSSEM/tree/master/data_dictionaries/windows/sysmon
https://docs.google.com/spreadsheets/d/1Y3MHsgDWj_xH4qrqIMs4kYJq1FSuqv4LqIrcX24L10A/edit#gid=0


## Real-time News Streaming Optimized for Wealth Solutions

* Last update: July 2021
* Environment: Windows and Linux OS
* Compiler: Python
* Prerequisite: RDP Credentials with Real-Time News Streaming Optimized service (Username, Password, ClientId)
- - - -
The example demonstrates:
1)	Authenticating to RDP Gateway
2)	Query VIPs from RDP Service Discovery
3)	Log-in Real-Time Streaming Optimized Service
4)	Retrieve Real-Time News
- - - -
Examples of command line usage:

python mrn_rdpgw_service_discovery.py --user YOURVALIDMACHINEID --password YOURVALIDPASSWORD --clientid YOURVALIDCLIENTID --mrn_ric MRN_STORY

python mrn_rdpgw_service_discovery.py --user YOURVALIDMACHINEID --password YOURVALIDPASSWORD --clientid YOURVALIDCLIENTID --region EMEA
- - - -
Uses RDP Market Price Service discovery example
https://github.com/Refinitiv/websocket-api/tree/master/Applications/Examples/RDP/python

Uses example of outputting Machine Readable News JSON data using Websockets 
https://github.com/Refinitiv-API-Samples/Example.WebSocketAPI.Python.MRN/tree/ERT-in-Cloud



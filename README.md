###Real-time News Streaming Optimized for Wealth Solutions###


Simple example of authenticating to EDP-GW and using the token to query VIPs
from EDP service discovery, login to the Refinitiv Real-Time OtimizedService, and
retrieve Machine Readable News (MRN) content. A username and password and client id are used to
retrieve this token.

Uses RDP Market Price Service discovery example
https://github.com/Refinitiv/websocket-api/tree/master/Applications/Examples/RDP/python

Uses example of outputting Machine Readable News JSON data using Websockets 
https://github.com/Refinitiv-API-Samples/Example.WebSocketAPI.Python.MRN/tree/ERT-in-Cloud


Example command line usage:

python mrn_rdpgw_service_discovery.py --user YOURVALIDMACHINEID --password YOURVALIDPASSWORD --clientid YOURVALIDCLIENTID --mrn_ric MRN_STORY
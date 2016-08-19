# First Alhpa version of the OpenInAClick Protocol (OIACP)
OIACP is the basic protocol to open a locker

The goal of OIACP is to be:
- A standard format; The protocol will have a standard format to handle lockers a digital way by the internet protocol.
- A small format; The protocol will have a small as possible format because of Internet of Things bandwidth performance.
- Secure; Since lockers are build to secure an environment in general, the protocol will have a secure basis.

Specification:

Server (Software using the protocol):
This will be the data sending to a locker
- Required: Unique ID of the locker
- Required: Requestcode ('1' = 'open', 2='status-request')
- Optional: Server name/version

Client (Locker):
If (not required) returning data to the server from the locker can send the following data
- Required: Unique ID
- Required: Status code 
- Optional: Vendor
- Optional: Product type
- Optional: locker client name/version

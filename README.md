# Trendify Nexus TCP Relay

## Railway variables
- PORT=443
- RELAY_SECRET: copy the value shown by the Installer

## Setup
1. Deploy this repository to Railway.
2. Set PORT=443 and RELAY_SECRET.
3. Create a TCP Proxy targeting internal port 443.
4. Add the TCP proxy host and port to the Gateway Worker variables.
5. Complete the V2 backend variables in the Gateway Worker before using it.

Never publish RELAY_SECRET.
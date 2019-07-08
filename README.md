# What
The technology addon "TA-indexed_ip" was designed as a proof of concept to capture the IP address as an index-time field for a Windows Endpoint within Splunk for every event similiarto the host field.

# How
TA-indexed_ip/default/serverclass.conf - should go to your deployment server

TA-indexed_ip/default/fields.conf - should go to your searchhead to be able to leverage the newly created index-time field: host_ip.

Everything else can be deployed to the Windows Universal Forwarder.

# Known Issues

**Script in default/inputs does not kick-off automatically as it should.**

## Disclaimer
Use this at your own risk, it's a proof-of-concept. 

This was created on my own and is not supported or endorsed by my employer.

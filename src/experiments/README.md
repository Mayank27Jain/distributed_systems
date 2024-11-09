### Setup
running receiver.py on one terminal and sender.py on same machine, different terminal

### Observations
Data transfer seems to happen, with all tested addresses in `127.0.0.1/8`.
However it is clear sender/receiver architecture, with no negotiation for mcast.

### Conclusion
It might be fine to fix a few temporary ports and then use IP addresses to handshakes for our setup.

### Next steps
We will attempt to create the mcast absraction. We should be able to do this with given materials.
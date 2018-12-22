# Web Service Discovery protocol amplification PoC (port 3702)

Yet another bloody UDP insecure service, this time similar to other abused SOAP protocols but needing no trigger payload.
Shodan showed 216,313 possible reflectors with the biggest number from Vietnam followed by United States.

I'm not Akamai so ill be waiting to see their report, but from what I can measure with overhead additions, the amps range from 50 to 150x.

I've scanned and filtered a list that will be alongside this script.

`WSD_3702.pkt - Zmap payload ("<\xaa>" or any WSD centric discovery payload will work)`
`wsd.c - Standard socket template with my corrections`
`wsd.list - Example amp list`

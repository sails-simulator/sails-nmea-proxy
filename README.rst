================
sails-nmea-proxy
================

Small proxy to emit NMEA data from sailsd. This allows tools such as OpenCPN to
be used with sailsd.

To test the output, try:

   socat -u udp-recv:10110,reuseaddr -

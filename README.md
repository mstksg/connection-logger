Connection Logger
=================

Short shell/bash script that might not have even been worth writing.

Continually pings the given server at the given interval and logs a
timestamped latency (or "n/a" if timeout) to stdout.  CTRL+C or kill to stop.

Useful for monitoring when your personal server goes offline.

Usage:

    connection-logger.sh PERIOD HOST TIMEOUT

Defaults to 15 second period, 8.8.8.8 (Google's DNS Nameserver), and 2 second
timeout.

`-h` for further details.


# Usage

This docker runs statsd with debug and dumpMessages enabled.

To start this container (detached) :

    docker run -d -p 8125:8125/udp hypnza/statsd_dumpmessages

Then view the logs to see incoming statsd messages:

    docker logs -f <hash_returned_from_command_above>

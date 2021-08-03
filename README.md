
# Docker Compose

Learning more about docker-compose. This example brings up 3 nginx web servers with an nginx load balancer in front of them.
The app running in PHPPM will print the name/ip of the server that served the request.
<pre>
                                / WEB1 \
 BROWSER/HOST <-> BALANCER <-> |  WEB2  | <->  PHPFPM
                                \ WEB3 /
</pre>

docker-compose up

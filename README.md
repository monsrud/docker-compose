
# Docker Compose

Learning more about docker-compose. This example brings up 3 nginx web servers with and nginx load balancer in front of them.
The app running in PHPPM will print the name/ip of the server that served the request.

>              / WEB1 \
>  PHPFPM <-> |  WEB2  | <->  BALANCER  <- HOST ->  BROWSER
>              \ WEB3 /


docker-compose up

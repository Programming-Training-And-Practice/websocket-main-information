# Websocket Main Information.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Pros.](#pros)
* [Cons.](#cons)
* [Other solutions based on WebSockets.](#other-solutions-based-on-websockets)
* [Help](#help)





## About.





## Documentation.





## Pros.
* No Overhead ~ TCP
* Integrates well in browser.
* Cover all communication cases(request,response,serverStreaming,clientStreaming).
* Pin-pong connection(client sends to server 'pin' and server response 'pong'). Thus, our client and server always 
  know that there is someone alive on the other side, or he is no longer responding.





## Cons.
* Complex Development (especially using reactive programing).
* Average Performance.
* Lack of Resilience (no Back Pressure).





## Other solutions based on WebSockets.
* SockJS + STOMP
* Socket.io





## Help.

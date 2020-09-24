1. Scalability.
   1. Case-Study : Node.js
      1. [Comparision of how node vs other web frameworks hadles requests : Overall idea(but half truth)](https://www.journaldev.com/7462/node-js-architecture-single-threaded-event-loop)
      1. [  How, in general, does Node.js handle 10,000 concurrent requests?](https://stackoverflow.com/questions/34855352/how-in-general-does-node-js-handle-10-000-concurrent-requests)
      2. [  Is non-blocking I/O really faster than multi-threaded blocking I/O? How?](https://stackoverflow.com/questions/8546273/is-non-blocking-i-o-really-faster-than-multi-threaded-blocking-i-o-how)
      3. [Why so many threads hurts performance ?](https://www.codeguru.com/cpp/sample_chapter/article.php/c13533/Why-Too-Many-Threads-Hurts-Performance-and-What-to-do-About-It.htm)
      4. [Why cpu bound is better with blocking I/O and I/O bound is better with non blocking I/O](https://stackoverflow.com/questions/34877705/why-cpu-bound-is-better-with-blocking-i-o-and-i-o-bound-is-better-with-non-block)
      6. [Demystifiying epoll()](https://jvns.ca/blog/2017/06/03/async-io-on-linux--select--poll--and-epoll/)
   5. [(Advanced) C10k problem](http://www.kegel.com/c10k.html)
2. Networks
   1. [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/html/#client-server-background)
   2. [Networking-HTTP : Evolution of HTTP](https://medium.com/platform-engineer/evolution-of-http-69cfe6531ba0)
   3. [Networking-HTTP, Websockets : HTTP and Websockets: Understanding the capabilities of today’s web communication technologies](https://medium.com/platform-engineer/web-api-design-35df8167460)
   4. [Networking-HTTP : Squeeze the juice out of Node— an exploration of how Node.js handles HTTP connections](https://www.yld.io/blog/squeeze-the-juice-out-of-node-an-exploration-of-how-node-js-handles-http-connections/)
   5. [Difference between sockets and ports](https://stackoverflow.com/questions/152457/what-is-the-difference-between-a-port-and-a-socket#:~:text=A%20socket%20represents%20a%20single%20connection%20between%20two%20network%20applications.&text=A%20port%20represents%20an%20endpoint,without%20interfering%20with%20each%20other.)
   6. [TCP: can two different sockets share a port?](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=5%20Answers&text=A%20server%20socket%20listens%20on%20a%20single%20port.&text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)
   7. [How do multiple clients connect simultaneously to one port, say 80, on a server?
](https://stackoverflow.com/a/11344212/6753380)
   8. [Does the port change when a server accepts a TCP connection?
](https://stackoverflow.com/questions/2997754/does-the-port-change-when-a-server-accepts-a-tcp-connection)
   9. [How does a browser establish connection with a web server on 80 port? Details?
](https://stackoverflow.com/questions/35387835/how-does-a-browser-establish-connection-with-a-web-server-on-80-port-details)
3. RealTime
   1. WebSockets
      1. [https://www.youtube.com/watch?v=sUEq35F-ELY](https://www.youtube.com/watch?v=sUEq35F-ELY)
      1. [Intro and code in nodejs, has more links in descriprition](https://www.youtube.com/watch?v=2Nt-ZrNP22A&t=979s)
      1. [Do you really need WebSockets?](https://blog.stanko.io/do-you-really-need-websockets-343aed40aa9b)
   2. Socket.io
      1. [Video : Introduction in nodejs](https://www.youtube.com/watch?v=soerr09FYCw)[; Get started with socket.io](https://socket.io/get-started/chat/) 
      2. [Video : Namespaces, Rooms and Connections in nodejs](https://www.youtube.com/watch?v=bxUlKDgpbWs) 
   3. Performance 
      1. [Resources consumption for Websockets, long polling, http](https://qiuzhihui.gitbooks.io/r-book/content/system-design/short-polling-v-long-polling-vs-websocket.html)
      3. [Resources consumption for Websockets, long polling, short polling](https://www.diva-portal.org/smash/get/diva2:1133465/FULLTEXT01.pdf)
      5. [Network Bandwidth : At what point are WebSockets less efficient than Polling ?  (Do read comments)
      ](https://stackoverflow.com/questions/44731313/at-what-point-are-websockets-less-efficient-than-polling)
      6. [What is the fundamental difference between WebSockets and pure TCP? (Do read comments)
](https://stackoverflow.com/questions/2681267/what-is-the-fundamental-difference-between-websockets-and-pure-tcp?rq=1)
      7. [Differences between TCP sockets and web sockets, one more time [duplicate]
](https://stackoverflow.com/questions/2681267/what-is-the-fundamental-difference-between-websockets-and-pure-tcp?rq=1)
      7. [How WebSocket server handles multiple incoming connection requests?
](https://stackoverflow.com/questions/28516962/how-websocket-server-handles-multiple-incoming-connection-requests?noredirect=1&lq=1)
      9. [Why websocket needs an opening handshake using HTTP? Why can't it be an independent protocol?
](https://stackoverflow.com/questions/19568432/why-websocket-needs-an-opening-handshake-using-http-why-cant-it-be-an-independ/19569871#19569871)
      10. [Proxying WebSockets with TCP load balancer without sticky sessions
](https://stackoverflow.com/questions/15266702/proxying-websockets-with-tcp-load-balancer-without-sticky-sessions/15270860#15270860)
      11. [Socket-io : Performance for sending ping pong messages](https://stackoverflow.com/questions/49865832/pingtimeout-and-pinginterval-in-socket-io)
   4. Misc.
      1. [Realtime, Event-driven APIs Concepts Articles series](https://www.ably.io/concepts)
      4. [Pubnb blogs on real time systems](https://www.pubnub.com/blog/)
3. Sessions 
   1. [Sticky Sessions](https://stackoverflow.com/questions/10494431/sticky-and-non-sticky-sessions)[ Sticky Session](https://www.imperva.com/learn/availability/sticky-session-persistence-and-cookies/)
4. General Programming
   1. [Difference between compiled and interpreted languages?
](https://stackoverflow.com/questions/38491212/difference-between-compiled-and-interpreted-languages/38491646#38491646)
5. Authentication
   1. [What is Firebase? The complete story, abridged.](https://medium.com/firebase-developers/what-is-firebase-the-complete-story-abridged-bcc730c5f2c0)

###### <p align="right">  By: Claire Wang & Ashley Joseph</p>

## **HOW DOES THE INTERNET WORK?** 

> ### **Contents**
- **What is the Internet** <br><br>Early 1970’s, Vint Cerf (co-creator) and Bob Kahn worked the design of the Internet <br>The Internet is a result of another experiment: Arpanet (Advanced Research Projects Agency Network) <br><br>Arpanet – Defense department research project <br>Paul Baran (Computer Network Pioneer) tried to build up a communication system and decided to use a distributed packet-switched network (to break up messages 	into blocks and sending them as fast as possible in every possible direction through the mesh network). Became a nationwide experimental packet network and the 	experiment worked successfully <br><br>Internet is made up of large numbers of independently operated networks. The system is fully distributed and no central control. These large numbers of 	operated networks are all business decisions that are made independently by the operators. They are all motivated to assure that there is end-to-end connectivity of every part of the network. The utility of the net is to let any device to communicate with any other device. 


- **Wires, Cables, Wifi** 
<br><br>Internet – a tangible physical system made to move information <br>Internet sends binary information. Information is made up of bits. A bit can be described as paired opposites and typically use “1” and “0”. Ex) On or Off, Yes 	or No. Because bits can have two possible states, it’s called a binary code.

   - 1 Byte = 8 Bits
   - 1 Kilobyte = 1000 Bytes
   - 1 Megabyte = 1000 Kilobytes
 
  <br><br>Everything on the internet is represented by bits. Bits are the atoms of information <br>Physically send bits by electricity, light, and radio waves.
   - Electricity – 
     - Sending bits information via electricity. Operators can use time to send bits and receiver will record the code over time. 
       - Bandwidth: transmission capacity, measured by bitrate
       - Bitrate: the number of bits per second a system can transmit
       - Latency: time it takes for a bit to travel from sender to receiver
     - Pro: Cheap, Con: Signal Loss
     - Sending information through wire

   - Light –
     - Light is faster than electricity
     - Pro: Fast & No Signal Loss, Cons: expensive & hard to work with
     - Sending information by fiber optic cable (is a thread of glass engineered to reflect light)
     - When sending a beam of light down the length of the cable, it bounces left and right till it’s received to the other end.<br> Depending on the bounce angle, it can send multiple bits simultaneously at the travel speed of light. Can use it across ocean floors. 

   - Radio Waves –
     - Radio waves – Is a wireless bit sending machine uses radio signals to send bits from one place to another. 
     - The machine needs to translate the 1’s and 0’s into radio waves of different frequencies. The receiving machines reverse the process and convert it back to binary code computer
     - Pro: Wireless, Con: Signal Loss
     - Cannot use for long distance




- **IP Addresses and DNS** <br><br>In 1970’s there were no standard method for networks to communicate. <br>Vint Cerf (voted most likely to co-invent internet) and Bob Kahn (voted most passionate about protocols) invented networking protocol to make network 	communication possible which was the groundwork of network. <br>Internet – is a network of networks. It links billion of devices together all around the world. <br>Ex) laptop/phone connect to internet thorough wifi, and wifi connect to ISP (Internet Service Provider), and ISP connect to billions of devices all around the 	world through hundreds and thousands of networks that are all interconnected. <br>Internet – the internet is a design philosophy and architecture expressed in a set of protocols. <br>Protocol – a well-known set of rules and standards used to communicate between machines. <br><br>All the different devices on the internet have unique addresses. <br>Address – address on the internet is just a number that’s unique to each device on the network. Ex) 141.72.251.38. <br><br>IP (internet protocol) - one of the most important protocols used in internet communication <br>IP address – a computer’s address. It’s organized in a hierarchy. Each IP address number are represented in bits. Traditional IP address is 32 bits long, 8 	bits for each part. <br><br>We are now using IPv6 version – 128 bits per address, provide 340 undecillion unique addresses <br><br>DNS (Domain Name System) – associate names (www.example.com) with a corresponding address (141.72.251.38.). Computer uses DNS to look up the main name and get 	associate IP address, which is used to connect computer to destination on the internet. <br><br>DNS servers are connected in a distributed hierarchy and splitting up responsibility for the major domains (.org/.com/.net). <br><br>DSN was created to be an open public communication protocol (from government and educational institution). DNS is susceptible to cyber-attacks. <br><br>DNS Spoofing – when a hacker attacks a DNS server and changes it to match the domain name with a wrong IP address. This let the attacker to send people to one of the fake websites. If attacked, the user is using a fake website as if it is real. <br><br>DNS and IP are designed to scale no matter how much the internet grows 





- **Packets, Routing and Reliability**  <br><br>The way information gets transferred from one computer to the other:  information need not follow a fixed path. Information on the internet goes one computer 	to the other in packet of information. <br><br>Many kinds of digital information can be sent with IP packets, but there are limits. The computer can send the digital information by breaking into packets. Each packet has the internet address of where it came from and where it’s going. <br><br>Routers – a special computers on the internet. Act like traffic managers to keep packets moving through the internet smoothly. Packets arrive at destination at 	different times and out of order. <br><br>Internet Protocol – every router keeps track of multiple paths for sending packets and chooses the cheapest path for each piece of data based on destination IP address for the packet. Having option for paths makes the internet fault tolerant (network can keep sending packets even if something goes wrong). <br><br>TCP (transmission control protocol) – manages the sending and receiving of all your data as packets. <br>Ex) when requesting a song from your device, the song will be broken into many packets. When packets arrive, TCP does a full inventory and sends back acknowledgements of each packet received. If all packets arrived, TCP signs for delivery. For each missing/incomplete packet, the server will resend 		them. Once TCP verify the delivery of many packets from that requested song, the song will start to play. <br><br>TCP + Router systems are scalable (can with many devices). Because of principle of fault tolerance of redundancy, the more routers we add the more reliable the internet becomes. Can grow and scale the internet without interrupting service for anybody using it.  <br><br>The internet is made up of networks and devices connected physically. These different systems that make up the internet connect/communicate/collaborate to each 	other because of agreed upon standards for how data is sent around the internet. Computing devices/routers along the internet help all the packets made their 	way to the destination where packets are reassembled in order. 



- **HTTP and HTML** <br><br> Web Browser: it’s an app to access web pages. On the web page, type in URL(uniform resource locator)/web address <br><br>A computer will ask the server to access a website and the server starts to talk back through HTTP. <br><br>HTTP (hypertext transfer protocol) – the language used to communicate between browsers and servers. <br><br>“GET” requests – using HTML code. Ex) GET /login HTTP/1.1 Host: www.tumblr.com <br><br>HTML (hyper text markup language) – the language to tell the web browser how to make the page look. <br><br>The text of a webpage is included directly in the HTML, but other parts like images/videos are separate files with unique URLs. The browser sends separate HTTP 	requests for each of these and displays them as they arrive.<br><br>“POST” request – a post to a webpage that has some data attached to it and goes to the webpage server and the server figures out and sends the webpage back to 	the browser and attached an invisible COOKIE data that the browsers see and knows to say. The we browser holds to the COOKIE ID number and the next time the 	web site refreshed, the web browser automatically attach that ID number with request that sends the server, so the server will see the request + ID number and 	knows the request from the user.  <br><br>Cookies – what websites use to remember who you are. An ID number that remembers who you are<br><br>Internet – Is completely open, the connections are shared, and the information is sent in plain text. <br>Safe websites prevent snooping + tampering by communicating on a secure channel using SECURE SOCKETS LAYER + TRANSPORT LAYER SECURITY. <br><br>SSL (secure sockets layer) and TLS (transport layer security) are a layer of security around your communications. SSL + TLS will appear as a lock icon on the 	browser address bar next to the HTTPS. <br><br>HTTPS (hyper text transfer protocol secure) – ensure the http request are secured and protected. When a website ask the browser to engage in a secure 	connection, it first provide the DIGITAL CERTIFICATE (which is like an official ID card) proving that the it’s the website as claimed to be. <br><br>Digital certificate – are trusted entities that verify identities of websites and issue certificates for them <br><br>HTTP + DNS – manage the sending and receiving of web files <br>TCP/IP + Routing – breakdown and transport packets <br>Packets are made up of binary sequences of 1’s and 0’s are sent physically (electric wires, fiberoptic cables, and wireless networks)



<br>
For video reference, click on ===> "<a href="https://youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7"> :desktop_computer: </a>"



**Title**
Exploring the route of sending packet. 

**The Problem**
Sometimes, we may need to find out why the client cannot reach the server. Is it because of congestions or broken link, or malfunctioned router? Sometimes we may also need to know why the latency is not expected. Because during the real-time communication latency is an important factor. After finding out the hop’s IP addresses, we can find out the geolocation (using the third party) where the packet is getting lost or the traversing area of the packet. For these reasons, I get “Exploring the route of sending packet” is an interesting topic.

**The Solution**
The primary goal of this project is finding out the IP addresses of intermediary nodes. Then, based on the explored IP addresses, I will try to reach a decision that there is any congestion or broken link, or malfunctioned router (for some cases) in the route. I will also try to find out hop to hop traveling time of packets.   

**Networking Components**
* UDP
* ICMP
* TTL
* RTT

**Milestones**
_End of March:_ I want to reach my primary goal that finding out the IP addresses of intermediary nodes.
_End of April:_ I want to reach my secondary goal that how I can make the decision that there is any congestion or broken link, or malfunctioned router, and hope to hop traveling time.

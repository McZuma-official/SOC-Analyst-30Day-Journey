Core Concepts

Wireshark: A packet analysis tool used to capture and inspect network traffic across OSI layer

Packet Structure: Consists of headers(IP, TCP/UDP ports) and payload (data/content)

Pane View
Packet List: View of capture packets
Packet Details: Breakdown of selected packets by OSI layers
Packet Bytes: Raw hexadecimal and ASCII text payload

Some display filters
http: Isolates unencrypted HTTP web traffic
dns: Isolates dns queries and responses
ip.addr: Filters traffic involving a specific IP address (source or destination)
ip.src: Filters traffic coming strictly from a specific source IP
http.request.method == "GET" : Filters down to webpage or file download requests
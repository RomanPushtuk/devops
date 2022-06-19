### osi model

| level        | protocols                  |
|--------------|----------------------------|
| application  | http, http2, ftp, ssh, dns |
| presentation | ssl, ssh, ftp              |
| session      | sockets synch              |
| transport    | tcp, udp                   |
| network      | (packets)ip, icmp          |
| data link    | (frames)ethernet           |
| physical     | (bits)                     |

### tcp and udp
| tcp                                            | udp                                               |
|------------------------------------------------|---------------------------------------------------|
| connection oriented protocol                   | connectionless protocol                           |
| slower                                         | faster                                            |
| uses handshake protocols such as SYN, SYN-ACK  | do not use handshake protocol                     |
| do errors check and recover packages           | also do error check but discards broken packages  |
| do acknowledgment segments                     | do not acknowledgment segments                    |


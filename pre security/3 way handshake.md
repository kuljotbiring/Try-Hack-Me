| Step   | Message | Description |
| ------------- | ------------- | ------------- |
| 1  | SYN  | A SYN message is the initial packet sent by a client during the handshake. This packet is used to initiate a connection and synchronise the two devices together |
| 2  | SYN/ACK  | This packet is sent by the receiving device (server) to acknowledge the synchronisation attempt from the client. |
| 3  | ACK  | The acknowledgement packet can be used by either the client or server to acknowledge that a series of messages/packets have been successfully received. |
| 4  | DATA  | Once a connection has been established, data (such as bytes of a file) is sent via the "DATA" message. |
| 5  | FIN  | This packet is used to cleanly (properly) close the connection after it has been complete. |
| #  | RST  | This packet abruptly ends all communication. This is the last resort and indicates there was some problem during the process. For example, if the service or application is not working correctly, or the system has faults such as low resources.  |

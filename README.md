# Verteilte_Systeme

UDP Client and Server 
select() used in client to wait for feedback from Server. 
Client waits a few seconds for server response. 
If Server doesnt respond, client tries to send data again.
After 3 attemts,  client program aborts if no feedback from server. 

Server and Client use recvfrom() and sendto() to communitcate.

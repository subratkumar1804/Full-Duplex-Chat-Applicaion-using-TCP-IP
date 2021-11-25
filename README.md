# Full-Duplex-Chat-Applicaion-using-TCP-IP

<h4>REQUIREMENTS :</h4>
There are two hosts, Client and Server. Both the Client and the Server exchange message
i.e. they send messages to and receive message from the other. There is a two way communication
between them.


<h4>OBJECTIVE :</h4>
To implement a full duplex application, where the Client establishes a connection with the
Server. The Client and Server can send as well as receive messages at the same time. Both the Client and
Server exchange messages.


<h4>DESCRIPTION :</h4>
In full-duplex operation, a connection between two devices is capable of sending data in both directions simultaneously. 
Full-duplex channels can be constructed either as a pair of simplex links (as described above) or using one channel designed to permit bidirectional simultaneous transmissions. 
A full-duplex link can only connect two devices, so many such links are required if multiple devices are to be connected together.

<h4>HOW TO RUN :</h4>
<p>* Download the code from repository.</p>
<p>* Save the file on local PC/Laptop.</p>
<p>* If you have Linux Terminal then directly go to the terminal copy paste the code compile it and execute it(You have to open two terminals, one for server and other for client).</p>
<p>* If you are running it on windows then go to the microsoft store and download ubuntu terminal and execute it as shown below.</p>
<p>* SAMPLE OUTPUT:</p>
        <p>Server:</p>
          <p>(Host Name:Root1)</p>
          <p>[root@localhost 4ita33]# vi fserver.c</p>
          <p>[root@localhost 4ita33]# cc fserver.c</p>
          <p>[root@localhost 4ita33]# ./a.out</p>
          <p>Server is running.......</p>
          <p>Enter the input data:</p>
          <p>Received message from the client:hi</p>
          <p>how are u</p>
          <p>Data sent…</p>
<p>* SAMPLE OUTPUT:</p>
        <p>Client:</p>
          <p>(Host Name:Root2)</p>
          <p>[root@localhost 4ita33]# vi fclient.c</p>
          <p>[root@localhost 4ita33]# cc fclient.c</p>
          <p>[root@localhost 4ita33]# ./a.out 127.0.0.1</p>
          <p>Enter the input data: hi</p>
          <p>Data sent…</p>
          
<h4>INFERENCE :</h4> 
<p>*Thus the chat application full duplex communication is established by sending the request from the client to the server, server gets the message and gives response to the client and prints it.</p>

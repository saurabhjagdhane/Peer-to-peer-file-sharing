CONTENTS OF THIS FILE
---------------------
   
 * Introduction
 * Requirements
 * Execution
 
 
#####################
	INTRODUCTION
#####################

The objective of this project is to develop a simple peer-to-peer (P2P) File sharing system that uses a
centralized directory server. It consists of three components:
1. A brief survey summarizing existing P2P architectures for filele sharing.
2. A design of your P2P file sharing system, including its protocols.
3. A demonstration of your P2P system using at least three different hosts.


#####################
	REQUIREMENTS
#####################

1. Windows opearting system: version 7/8/8.1
2. 4 different hosts/Computers 
3. Python shell or python version 2.7.6 (should include binary in windows system to run through command window)

* To Download Python: https://www.python.org/downloads/
* To run python(.py) programs from command prompt: https://www.youtube.com/watch?v=IokKz-LZsEo


#####################
	EXECUTION
#####################
In code folder there are 4 folders as follows:
1. myserver
2. myclient1
3. myclient2
4. myclient3

Steps and instructions:
-----------------------
1. Each of the above folder includes python program to be executed on different hosts.
2. Locate the folder where .py program is present using cd command. 
3. To run a program in command prompt use:
								python myserver.py
								python myclient1.py
								python myclient2.py
								python myclient3.py
						
3. Hosts running myclient program will update the directory server with its contents when up and running using inform and update input:1
4. If any of the host wants to download a file then input:2
5. If host wants to exit the peer to peer system then input:3

6. Suppose myclient1.py wants to downlaod a file:
									Query for content, input=2:
7. then user is supposed to enter the desired filename which any of the other client in p2p system may have. In our case, asu.txt
8. Server will return the information about client name, ip address and port no of hosts running as myclient2.py and myclient3.py as they contain sample7.txt
9. Select any of the clients and enter their host and port name to downlaod a file.
10. Follow on screen instructions to ensure if you want to download a file.

##################
Download complete!
##################
--------------------------------------------------------------------------------------------------------------------------------------------



								




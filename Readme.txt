Project 2 Gossip Simulator
Team Members: 
Vishal Kumar Munka
UFID: 8128-6177
Snigdha Anupam
UFID: 6198-7948

What is working?
We have implemented both the Gossip and Push-Sum algorithms for the below four topologies using Akka actors:

	Full Network
	2D Grid
	Line
	Imperfect 2D Grid

Full Network:
To run Gossip algorithm using Full network topology the command is as follows:
 scala project2.scala 10 full gossip
To run Push-Sum algorithm using Full network topology the command is as follows:
 scala project2.scala 10 full pushsum

2D Grid: 
To run Gossip algorithm using 2D network topology the command is as follows:
 scala project2.scala 10 2D gossip
To run Push-Sum algorithm using 2D network topology the command is as follows:
 scala project2.scala 10 2D pushsum

Line:
To run Gossip algorithm using Line network topology the command is as follows:
 scala project2.scala 10 line gossip
To run Push-Sum algorithm using Line network topology the command is as follows:
 scala project2.scala 10 line pushsum

Imperfect 2D Grid:
To run Gossip algorithm using Imperfect 2D Grid network topology the command is as follows:
 scala project2.scala 10 imp2D gossip
To run Push-Sum algorithm using Imperfect 2D Grid network topology the command is as follows:
 scala project2.scala 10 imp2D pushsum

What is the largest network you managed to deal with for each type of topology and algorithm?

Gossip Algorithm:
Full Network
For nodes= 50000 we are getting the total time for Full network using Gossip algorithm as 440.133 seconds
2D Grid
For nodes= 50000 we are getting the total time for 2D using Gossip algorithm as 91.426 seconds
Line
For nodes= 40000 we are getting the total time for Line using Gossip algorithm as 560.364 seconds
Imperfect 2D Grid
For nodes = 50000 we are getting the total time for imp2D using Gossip algorithm as 376.556 seconds


Push-Sum Algorithm:
Full Network
For nodes= 20000 we are getting the total time for Full network using Gossip algorithm as 513.789 seconds
2D Grid
For nodes= 5000 we are getting the total time for 2D using Gossip algorithm as 1600.212 seconds
Line
For nodes= 5000 we are getting the total time for Line using Gossip algorithm as 1746.66 seconds
Imperfect 2D Grid
For nodes = 15000 we are getting the total time for imp2D using Gossip algorithm as 325.792 seconds


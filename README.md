# Java-Love-Letter-Game

# Set Package According to your file Structure 

Step 1 <> Firstly Go to java folder & 
Step 2 <> Then open Command Prompt 
Step 3 <> Set Classpath (Temporarily )
set CLASSPATH=.;
Step 4 <> Run By Using this Command 
javac client/*.java lovelettergame/*.java
Step 5 <> Firstly Run Server By Using This Below Command 
java org.example.client.Server
Step 6 <> Open Another Terminal (On the Same Place of Java folder )
javac org/example/client/Client.java
Step 7 <> Then Run java org.example.client.Client
Step 8 <> Write Username & Enjoy Game 
For Create Game use Command 
Step 9 <> /creategame 
Step 10 <> /joingame 
Step 11 <> /startgame 
Step 12 <> /playcard 
For playing Cards 
Step 13 <> /secretcardsend
For Secret Card Send Yourself
Step 14 <> DirectMessage Tag like that 
@username Message 
1(a) Direct Message Requirement 
1(b) Only One Game can Create per server 
1(c) A client can join the game if it has not yet started
1(d) when enough players have joined min. 2, max 4
// Server will stop working When players are less than 2 & Graeter than 4 
As in below example only one user 
1(e) . /score 
2(a) Server informs all ends of the game about game events
2(b) Players can play a card
2(c) Players are each sent their own cards in secret
//Proper Error Handling with Code Comments 

# amici
terminal based "network" named Amici, representing persons and friends of persons who have joined the system.

Initially, the Amici network is empty, having no people in it. As the program processes input lines, people are added to the database, friendships are created and destroyed, and information about the network is printed. This continues until the program runs out of input, at which point the contents of the database will be printed and the program will terminate.

The program must be able to handle any number of users, and must be able to handle any number of friendships per user. You do not know how many people will be added to your network, and you do not know how many friendships will be created for any people in the network, which means you cannot declare arrays to hold this information. You must use dynamic storage for this.


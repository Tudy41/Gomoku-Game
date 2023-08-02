## AdvancedProgramming2023 - Lab 10

# Compulsory

----

- [x] Create the project ServerApplication. This will contain (at least) the classes: GameServer and ClientThread.
- [x] Create the class GameServer. An instance of this class will create a ServerSocket running at a specified port. The server will receive requests (commands) from clients and it will execute them.
- [x] Create the class ClientThread. An instance of this class will be responsible with communicating with a client Socket. If the server receives the command stop it will stop and will return to the client the respons "Server stopped", otherwise it return: "Server received the request ... ".
- [x] Create the project ClientApplication. This will contain (at least) the class: GameClient.
- [x] Create the class GameClient. An instance of this class will read commands from the keyboard and it will send them to the server. The client stops when it reads from the keyboard the string "exit".

----

# Homework

----

- [x] Implement functionalities of the game, using the classes Game, Board, Player, etc.
- [x] The clients will send to the server commands such as: create game, join game, submit move, etc.
- [x] The server is responsible with the game management and mediating the players.
- [x] The games will be played under time control (blitz) with each player having the same amount of time at the beginning of the game. If a player's time runs out, the game is lost.


----

# Bonus

----

-[ ] Implement a feature for organizing tournaments.
 Assuming there are n players registered on the server, create a schedule such that:
 each player will play with every other player exactly once (colors are chosen randomly);
 a player can not have more than p games in a day;
 the tournament must finish in at most d days.
 You may use an ILP (Integer Linear Programming) solver, such as Gurobi, CPLEX or OR-Tools.
-[ ] Once the schedule is created, generate random outcomes for all games (there are no draws).
 Find the sequence of players p1,p2,...,pn such that pi beats pi+1, for all i=1,n-1.
 You may use Graph4J.

---- under time control (blitz) with each player having the same amount of time at the beginning of the game. If a player's time runs out, the game is lost. (solved) (Folosind un obiect din clasa *Timer*, pastrez evidenta fiecarei ture in parte, astfel incat ca timpul sa se opreasca cand se termina tura jucatorului 1 si incepe tura celui de-al doilea jucator, acesta reluandu-se.)

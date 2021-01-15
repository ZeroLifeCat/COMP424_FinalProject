# SaboteurComp424
# Saboteur Gameplay
Players are assigned either a "Miner" or a "Saboteur" role, and given a mixed hand of path and action cards, and take turns in succession playing one card from their hand (or discarding it) and collecting a new one from the draw pile.

Miners may play a path card in order to progress in building a tunnel from a special card which represents the mine start to one of the three special cards that represent possible gold locations (only one of which is effectively gold, but the players do not know which when the game begins as they are placed face down), while Saboteurs try to play path cards which actually hinder such progress (for example by ending paths or making them turn in opposite directions).

Either player can instead play an action card, which have varying effects such as blocking other players from building paths (breaking their tools, in the game's analogy) or unblocking themselves or other players (usually the ones they believe to share the same role of either Miner or Saboteur). Action cards can also be used to block other cards depending on the gamers' opinions.

There are three rounds of play, where each round is concluded by either reaching the treasure or running out of action cards.
# Goal of the agent
Reach the treasure before the ither human.

# Set up Guide
If using Eclipse and you've set it up as described above, you can easily start a game. Simply click Run in Eclipse, then click on GUI. This will launch the GUI for you. Then, click the launch tab in the GUI, and select Launch Server. Then, the frst client you launch will be the rst player; for example, select Launch Human Player next. Then, to set the second player, select the next client class; for example, select Launch Client (Saboteur.RandomSaboteurPlayer). You can now play against a random player in the GUI to get a feel for the game. Changing the Clients you select will determine who/what plays who/what - so you can run two humans against each other too, and similarly two agents against each other.

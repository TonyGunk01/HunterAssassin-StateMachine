# HunterAssassin-StateMachine

Hunter Assassin is a stealth 2D top view game where the player has to evade hunters and make it past them either silently or finish them off. The game is made in Unity 2D and programmed in C#.

Each enemy has a detection range, if the player is in the detection range, then the enemy goes after the player and attacks it. The player must evade out of the enemy range for sometime and then the enemy stops pursuing the player and goes back to its default position.

Adding new behaviours to the enemy can be complicated and results in lengthier spaghetti like code, hence I have implemented state machines. In my case, I have an enemy which only chases, patrols or stays idle. In the future, I may want to add more complex enemy types which have additional states like chasing, rotating, etc.

Video demo:

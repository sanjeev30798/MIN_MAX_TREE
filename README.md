# MIN_MAX_TREE
In the game of sticks there is a heap of sticks on a board. On their turn, each player picks up 1 to 3 sticks. The one who has to 
	pick the final stick will bethe loser. 

	 Human vs Human

		 create a game where two players can play against each other that always removes one or two or three sticks. Continue doing
		until it someone wins!

	 Human vs AI

		We're going to develop an AI that can learn to play the game better, with experience. Here's how we're going to do it.The AI
	    has a number of hats, one hat for each possible amount of sticks 
		on the table. Initially, each hat contains three balls that are numbered from 1 to 3. At every step of the game that the AI 
		plays, the AI selects a random ball from the hat that matches the amount of sticks currently on the board. When the AI chooses 
		a ball from a hat, it leaves it in the hat, but it needs to remember which one it picked, and then takes the amount of sticks 
		that the ball indicates.If the AI wins the game, it goes back through its memory of all the balls it picked. Since it won, these
		all most have been good choices! It then adds a another ball to each hat with the same number on it as the ball that it had 
		selected from that hat. If the AI loses, it will throw away a ball from each hat with the number that it selected from that
		hat. (Note: A hat must always have at least one ball of each number, hence the last ball of a specific number cannot be thrown 
	    away.)As more and more games are played, the good moves will be associated with having many more balls in the hats.

	AI vs AI

		 As we play against it, we notice 
		 that it takes a considerable amount of time before the AI is able to perform against a human player. In this part, you need to 
		 modify the program so that the player can choose to play either against a naive AI or a pre-trained AI.In order to pre-train 
		 an AI.

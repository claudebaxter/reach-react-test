#rock-paper-scissors-react

This is an attempt to deploy a reach react app to gh-pages.

You test the application on GH-Pages <a href=https://elborracho420.github.io/reach-react-test title="Rock Paper Scissors"> here.</a>

The game requires two players to play, who will each need an Algorand wallet with testalgos to play with. This decentralized application users smart contracts written with Reach, a form of javascript, and interacts with the testnet / developer net for the blockchain. You can look up the official test algo dispenser to get free test algo to play with.

The deployer (player 1) must prepare the contract code and share with the attacher (player 2) so that they can respond and agree to the bet. Each player chooses either rock paper or scissors after agreeing to the bet, and once submitting, the winner receives the pot.
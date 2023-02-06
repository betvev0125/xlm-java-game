# xlm-java-game

In this example, the XML code sets up a LinearLayout that contains a TextView widget to display the score and a Button widget to play the game.

The Java code sets up the MainActivity and uses the setContentView method to inflate the layout defined in the XML code. It retrieves references to the Button and TextView widgets using the findViewById method and sets an OnClickListener on the Button to play the game when it is clicked. The game is implemented in the play method, which generates a random score using the Random class. The score is then displayed on the TextView widget.

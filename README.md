# Python-Snake-Game
This is a Snake Game created using Python with storage of Game Data in MYSQL Database using pymysql.
It is a snake game consisting of a snake of characters, the snake initially is a '#' character and as it collects food(which are * characters)these characters are appended to the snake's body which makes it longer.You can direct the snake in different directions using the arrow keys.You get 10 points per food collected.If the snake hits a wall or heads into its own tail then the game will be over.As more and more food is collected the length and the speed of the snake increases thereby making the game harder.There are 3 difficulty levels in the game.Player scores are stored in MySql database.
Tkinter is used for creating the GUI.
pymysql is used for Database Access/Manipulation.
pygame.mixer module is used for some fancy sounds on different events during the game like for game over,collecting food and background music.
The food is spawned randomly anywhere on the canvas and the code handles conditions where the spawned food and the snakes body overlaps to avoid erroneus spawning of food.
The bind function is used to bind the game window to the keyboard input for arrow keys inorder to create events on use of the arrow keys and execute the respective functions when any of the arrow keys is pressed.
The Sound files can be changed or removed completely as per your preference.:)

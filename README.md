# JuggerSnake game  

This is a HBD gift to 霞，one of the biggest Juggernaut fans in the world.  
Original idea from @Catbot3. He is a great programmer and 4k player; wish he luck passing ex8.  
I don't have much to say, please enjoy this game as well as these music!
And HAPPY BIRTHDAY MY BITCH!!!!!

## Customization  

If you want to customize this game (add songs, change the snake picture, or swap the milestone images), open `snake.html` in a text editor and look for the **CUSTOMIZATION SECTION** at the top of the `<script>` block.  

• **Songs & covers** – edit the `SONGS` array with objects containing `coverUrl`, `songUrl`, `songName`, and optional `startTime`.  
• **Snake/food images** – change `SNAKE_IMAGE_URL` and the entries of `foodImages`.  
• **Milestones & sidebar** – adjust `MILESTONE_IMAGES`, `SIDEBAR_IMAGE_URL`, and `MENU_MUSIC_URL`.  
• **Board size / speed** – modify the `<canvas>` attributes and the `setInterval(update, …)` delay further down if desired.  
• Everything else is vanilla HTML/CSS/JS; feel free to tweak style rules or game logic yourself.

## Playing the Game

1. Open `snake.html` in a modern browser.  
2. Use the **Start Game** button.  
3. Control the snake with the arrow keys.  
4. Collect apples – some will change the music, others have no effect.  
5. Don't hit the wall or yourself!
6. Milestone events and a combo animation trigger every 25 apples.  

Your score increases by 10 per apple.

### Fun Facts

- The Juggernaut pictures are actually provided by 霞 herself! I don't even know she has so many of them.
- If you collect all the songs, something magical will happen......
- The menu music Happy Birthday is singed by AI Juggernaut; I extract his fantastic vocal from Evo.
- Juggernaut Saiko!

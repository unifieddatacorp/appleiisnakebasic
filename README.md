# appleiisnakebasic
A snake game for Apple II basic inspired by The Coding Train.

https://www.youtube.com/watch?v=7r83N3c2kPw

I haven't coded in BASIC since maybe middle school and then it was on TRS-80s, but nevertheless here is my feeble attempt at a snake game with various improvements such as a maze, scoreboard, welcome and game over screens, and multiple levels. 

Run it here: https://www.calormen.com/jsbasic/

... or here https://www.scullinsteel.com/apple2/

... or perhaps on a real Apple II!

Notes:
- **important, delay**: You'll **need** to set the delay on line 20 depending on which emulator you use. I've set it to 1,000 which is fine for the calormen emulator. For the sculinstell one you'll need to set this to 0 otherwise the game is unplayable. I don't have a real Apple II but I suspect it will need to be "0" there also.

- Some readability and cleanliness has been sacrificed in the name of speed, mostly around advancing and growing the snake. Unfortunately this makes the code a bit hard to follow, but hey it's BASIC.

- There are some parameters you can play with at the top of the file.

- It's far from perfect but I have to stop somewhere.

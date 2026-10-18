# MG3
## Devlog
1. The default value of a float is 0, int is 0, and bool is false. A string defaults to null in C#, which appears blank in the Unity Inspector.
2. Unity calls Update() automatically every frame while the GameObject and its component are active. Timer.Update() runs each frame and subtracts Time.deltaTime so the timer counts down based on the passed time.
3. When the game starts, TimerText.Start() calls BeginTimer() to start the game timer at 30 seconds. Then TimerText.Update() runs every frame. It gets the remaining time from the Timer and displays it on screen. Also, it checks whether the timer has finished. When time runs out, it calls GameOver(), which shows the GameOver screen and stops the player from moving.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
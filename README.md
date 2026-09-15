# 三 swap
A simple tile-swap game!

<img width="400" height="400" alt="Screenshot 2026-09-14 at 8 21 20 PM" src="https://github.com/user-attachments/assets/a82a648b-63fc-43eb-a788-fbe0c71ca622" />

By the way, 三 means three in Japanese, and I used this because this game generates a random 10 by 10 board that consists of three colors WHITE, BLACK, and GOLD. 

You are a player(circle) starting from the top left corner. **ARROW KEYS TO MOVE!**

Every tile you step on, the tile changes color.
The color order goes like this:
**WHITE>>GOLD>>BLACK>>WHITE**
The goal of this game is to make the whole board the **same color**.

 I was inspired by the “Lights Out” mathematical game!

 A really hard part for me was that if I do not set constraints, **it does not guarantee a possible puzzle when generated**. In fact, there's only a 1/3 chance it will be possible. This is because there are scenarios that all tiles are **BLACK** except one tile which is **GOLD**. The board is impossible to fix. I eventually overcame this obstacle by calculating for about half an hour.

Just to show you how the player moves and how the board changes:


https://github.com/user-attachments/assets/b76ccb8f-d1f3-4216-a9b9-ceed9ce3cf64

HAVE FUN!! :D

if you can, please tell me your time! 


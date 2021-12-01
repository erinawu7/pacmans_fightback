# Pacman's Fightback

## Introduction

This game is inspired by the famous Pac-Man, only this time, the ghosts are going to be running away from pacman.

For each level, the pacman wins after eating all the ghosts, try to finish all three levels as fast as possible!

## Start the Game

#### requirements

- Install Java
- Install [nand2tetris](https://www.nand2tetris.org/software)
- Download `pacmans_fightback/`

#### compile and run

> This guide is for Linux system, for other OS, please check [https://www.nand2tetris.org](https://www.nand2tetris.org)

1. Compile .jack files into .vm files
    ```
    bash nand2tetris/tools/JackCompiler.sh pacmans_fightback/
    ```
2. Start the VMEmulator
    ```
    bash nand2tetris/tools/VMEmulator.sh
    ```
3. In the VMEmulator, click **File -> Load Program**, then choose the directory `pacmans_fightback/`
4. Change the setting **View -> Animate -> No Animation**
5. Click **Run** to start the game

## How to Play

### Controls

- The **direction keys** can change pacman's direction. 
- Throughout the game, **enter key** is needed when hints are shown on the screen.

### Game Flow

#### welcoming

The welcome page is shown after starting the game, pressing enter will lead to level 1.

![](https://i.imgur.com/oXofkKt.png)

#### level 1

The game will not start until any of the direction keys is pressed.

![](https://i.imgur.com/7UzDxE7.png)

After all ghosts are eaten, press enter to play the next level.

![](https://i.imgur.com/O3dx4Aq.png)

#### level 2

The game will not start until any of the direction keys is pressed.

![](https://i.imgur.com/HijuPy0.png)

After all ghosts are eaten, press enter to play the next level.

![](https://i.imgur.com/JeRQmCV.png)

#### level 3

The game will not start until any of the direction keys is pressed.

![](https://i.imgur.com/SJfhWlL.png)

#### ending 

When all three levels are completed, the ending page is shown.The score will be higher when pacman finished the mission faster.

![](https://i.imgur.com/W4fzoxs.png)

## About

This is a final project of the course Introduction to Computer, NTU CSIE 2019.
# Coin Rush Runner

**Coin Rush Runner** is an exhilarating endless runner game developed using Java. In this game, players dash through vibrant environments, collecting coins and avoiding obstacles to achieve the highest score possible.

Watch the video below to see the game in action:

[![Watch the video](https://img.youtube.com/vi/7vZrtDYKcyY/0.jpg)](https://youtu.be/7vZrtDYKcyY)

## Prerequisites

**Java Development Kit (JDK)**: Version 8 or later is recommended. 

## Features

- **Endless Runner Gameplay:** Keep running as long as you can while dodging obstacles and collecting coins to increase your score.
- **Dynamic Obstacles:** Encounter a variety of moving and static obstacles that test your agility and reaction time.
- **Coin Collection:** Collect coins scattered throughout the level to boost your score. The more coins you collect, the higher your score.
- **Engaging Visuals:** Enjoy a vibrant, colorful environment that changes dynamically as you progress.

## Project Structure

```txt
RunningMan/
│
├── Entity/                     # Contains classes related to game entities, objects or characters
│   ├── <Class files here>      # Compiled .class files for entity classes
│
├── Frame/                      # Contains classes related to game frames 
│   ├── BackEnd.class           # Class for backend logic
│   ├── BackGround.class        # Class for background management
│   ├── BackImage.class         # Class for handling background images
│   ├── BackImageLogin.class    # Class for handling login background images
│   ├── End.class               # Class for managing the end screen
│   ├── GameFrame.class         # Main game window/frame class
│   ├── HelpFrame.class         # Class for help screen frame
│   ├── LoginFrame.class        # Class for login window/frame
│   ├── MenuFrame.class         # Class for menu window/frame
│   └── WindowFrame.class       # General class for handling window frames
│
├── Panel/                      # Contains classes related to game panels (UI components within frames)
│   ├── GamePanel$1.class       # Inner class for game panel
│   └── GamePanel.class         # Main class for the game panel
│
└── <Other Directories or Files>

```


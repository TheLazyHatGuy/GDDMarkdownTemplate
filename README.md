# GDDMarkdownTemplate
Game Design Document Markdown Template

This is meant to be used in GitHub wiki.
This template is based on the template by [Artjom Kurapov](https://kurapov.ee/rus/lab/game_development/#f191).

# Game Design Doc Table of Contents
1. [Copyright Information](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/1.-Copyright-Information)
2. [Version History](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/2.-Version-History)
3. [Game Overview](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview)

    1. [Game Concept](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#game-concept)
    2. [Feature Set](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#feature-set)
    3. [Genre](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#genre)
    4. [Target Audience](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#target-audience)
    5. [Game Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#game-flow)
    6. [Look and Feel](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#look-and-feel)
    7. [Project Scope](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#project-scope)
        1. [Number of locations](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-locations)
        2. [Number of levels](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-levels)
        3. [Number of NPC’s](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-npcs)
        5. [Number of weapons](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-weapons)
4. [Gameplay and Mechanics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics)

    1. [Gameplay](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#gameplay)
        1. [Game Progression](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#game-progression)
        2. [Mission/Challenge Structure](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#missionchallenge-structure)
        3. [Puzzle Structure](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#puzzle-structure)
        4. [Objectives](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#objectives)
        5. [Play Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#play-flow)
    2. [Mechanics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#mechanics)
        1. [Physics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#physics)
        2. [Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#movement)
            1. [General Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#general-movement)
            2. [Other Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#other-movement)
        3. [Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#objects)
            1. [Picking Up Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#picking-up-objects)
            2. [Moving Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#moving-objects)
        4. [Actions](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#actions)
            1. [Switches and Buttons](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#switches-and-buttons)
            2. [Picking Up, Carrying and Dropping](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#picking-up-carrying-and-dropping)
            3. [Talking](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#talking)
            4. [Reading](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#reading)
        5. [Combat](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#combat)
        6. [Economy](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#economy)
    3. [Screen Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-flow)
        1. [Screen Flow Chart](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-flow-chart)
        2. [Screen Descriptions](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-descriptions)
            1. [Main Menu Screen](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#main-menu-screen)
            2. [Options Screen](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#options-screen)
    4. [Game Options](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#game-options)
    5. [Replaying and Saving](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#replaying-and-saving)
    6. [Cheats and Easter Eggs](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#cheats-and-easter-eggs)
5. [Story, Setting and Character]()
    Story and Narrative - Specific details like scripts and cut scenes may not be in this document but be in the Story Bible.	8
    Back story	8
    Plot Elements	8
    Game Progression	8
    License Considerations	8
    Cut Scenes	8
    Game World	8
    General look and feel of world	8
    Area #1	8
    Characters	9
    Character #1	9
    Levels	10
    Level #1	10
    Synopsis	10
    Introductory Material (Cut scene?  Mission briefing?)	10
    Objectives	10
    Physical Description	10
    Map	10
    Critical Path	10
    Encounters	10
    Level Walkthrough	10
    Closing Material	10
    Interface	10
    Visual System	10
    HUD - What controls	10
    Menus	10
    Rendering System	10
    Camera	10
    Lighting Models	10
    Control System – How does the game player control the game?   What are the specific commands?	10
    Audio	10
    Music	10
    Sound Effects	10
    Help System	10
    Artificial Intelligence	11
    Opponent AI – The active opponent that plays against the game player and therefore requires strategic decision making (example, Civilization or Chess, how is it to be designed?	11
    Enemy AI – Villains and Monsters	11
    Non-combat Characters	11
    Friendly Characters	11
    Support AI	11
    Player and Collision Detection	11
    Pathfinding	11
    Technical – This may be abbreviated with most in the Technical Bible.	11
    Target Hardware	11
    Development hardware and software	11
    Development procedures and standards	11
    Game Engine	11
    Network	11
    Scripting Language	11
    etc.	11
    Game Art - This may be abbreviated with most of the content in an Art Bible.	11
    Concept Art	11
    Style Guides	11
    Characters	11
    Environments	12
    Equipment	12
    Cut scenes	12
    Miscellaneous	12
    Secondary Software	12
    Editor	12
    Installer	12
    Update software	12
    Management	12
    Detailed Schedule	12
    Budget	12
    Risk Analysis	12
    Localization Plan	12
    Test Plan	12
    Appendices	12
    Asset List	12
    Art	12
    Sound	12
    Music	13
    Voice	13

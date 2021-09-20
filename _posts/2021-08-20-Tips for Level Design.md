---
title: Notes For Level Design
date: 2021-08-20 18:30:00 +0800
categories: [游戏设计, Game Design]
tags: [Level Design, game, notes]     # TAG names should always be lowercase
---

# Notes for Level Design
---

## GDC 2016: 360 Approach for Open world Level Design 
---
Eamples: AC & Farcry
 
- Define approach zones
    - Add color to those zones for game design document.
    
- Distribute ingredients
    How to choos ingredients?
    - First choose a dimension:
        1. Difficulty
        2. Mission Phase
        3. Gameplay focus
            - Acrobatics
            - Stealth
            - Fight
        4. Emotional theme
        5. Narrative acts
        
    - List appropriate ingredients

    - Get in the engine and adapt


## GDC 2009 Hideo Kojima - Making the impossible possible

---

### Impossible wall
- Possible: Done before / Experienced 
- Impossible: Never Done Before / Inxperienced
- "Making the impossible possible" demands preconceviced notion be discard 

### The impossible wall in game design
- The foundation: Hardware and technology
- The software techinology
- Game design 


## GDC 2019 Level Design Workshop: The Level Design of God of War
---

- **Core pillars create focus** - Conflicts and learnings: Puzzle can also help to train combat techniques
        Putting it all together 

- **Metrics based game (God of War)** - Conflicts and learning: Shrubs may affect fail in edge detection
    - Metric: A desgin measurement that communicates gameplay
    - Metric emphasizing core pillars
    - Building codes document

- Achieving variety 
    
- **All levels sell a theme** - Conflicts and learning: Budget may be restricted / gamepaly may be repeated
    
- **All critical path levels unlock a new ability** - Conflicts and learning:

- Create format
      - Definition for format: The inisituive rules by which levels flow into one and another
      - Alternate term: The game's structure
      - All games have some kind of format
      - Players can perceive sessions

- **Clear exploration breaks**
      - "Shock Arrow", "Key Point", "Teach new ability"
      - Level to level flow

- **Hubs are not open world** - Conflicts and learning: Gameplay may be repeated
      - Definition: A centralized location from which spokes emit (Spread from center)

    - Hub Based Desgin
      - Anatomy of a hub: Central Core, Spokes, End Point
      - "Player always come back to the center"


## GDC 2016 Level Design Workshop: The illusion of Choice 

---

- **Paradox of choice**
- Familarity breeds liking


## GDC 2013: Ten Principles for good level design 

---

- Good Level design is fun to navigate 
  - Visual Language: Direct player to the right path 
  - Clarity & Flow: E.g. Mirror of the edge
  - Confusion is Good 
- Good level design dos not rely on words
  - The broken circle 
  - Three narrative typs:
    - Explicit
    - Implicit: Mise-en-scene  / Environmental Level Design - Use environement to tell stories 
    - Emergent: Player choice E.g. Hitman 
  - Good level design tells plyer what to do but not how to do
    - Nebulous objectives
    - 


## Zhihu Live from Clark Yang
---

### FFF - Form Follows Function

- Form follows function
  - Definition: The form design must based on the functional needs
  - Put functional needs first helps the designer to know the goal clearly
  - Ideas and innovations wont be limited with the performance form
  - It also helps for desgning a better form of art

### Internal Kernal Rational Design

- Definiation: The most basic, elementary design in a game; Connect player to the game
- Kernal: The core, the abstratest elements of a game
- Rational: Not emotional
- Principle of Internal Kernal Rational Design: Form follows function

### Create gameplay

- The funcitonal needs of gameplay
- Define the rules of the gameplay (Function)
- Define the skills/actions players can do (Function)
- Define the input of players (Function)
- Define the internal parameter (Function)
- Design level desgin model (Form)
- Desgin the reaction players would recevie (Form)  

Example: The movement module and input module of a game.

**Divide a game into smallest and deepest module when anaylzing a game**

 ### Player skill != Character ablilty

 ### Player Skill: 

- Physical skills
    1. Timing 
        - Player need to judge when and what input should to be taken during the gameplay
    2. Reflexion
        - Player need to make the correct input command when an un predicted event happened 
    3. Measurement
        - Player need to be familiar enough with the input device, in order to control the input length and how much need to be input
    4. Accuracy
        - Player need to make accurate input
    5. Stamina
    6. ...

- Mental skills
    1. Resource management 
        - Player need to manage the **limited** resource in game
    2. Tactic (In short term)
        - Player need to make the right decision in a short/limited term based on the situation
    3. Strategy (For a long period)
        - Player need to make a plan for a long term goal based on limited information
    4. Logic anaglyze 
        - Player need to gather the info and find the logic inside info, to make a good decision
    5. Association 
    6. Obervation
    7. Focus
    8. ...

- Social skills
    1. Coorperation 
    2. Leadership
    3. Convence Ablity
    4. Communication 
    5. Desisive
    6. ...

### Define the parameters based on gameplay mechanics

- **Ignore the dispersed parameters**
  - E.g. A object move with a change in movement -> movement with low / high speed (IGNORE THE "CHANGE", JUST "SPEED")
  - Reduce the number of parameters (2~6) 
- **Make the parameters abstract**
  - Focus on gameplay mechneics' CORE 
- **Let every single gameplay mechneic has it own parameter for controlling itself**

    </n>

- Think without form but the core inside a form; Do not put mind into a specific senario when desgining a game
  
### Method to list parameters for a exsiting game

- From the internal: Think about the relationship between player's skills and input.

### **Parameters -> Gameplay Elements -> Level Design Modular**

### Gameplay Element and Level Design Module

- Definition of gameplay element: Put the parameters together
- Definition of level design modular: Levels contains gameplay elements, combining them and use them to change parameters [System]

### Player Mental Skill Focused Mechanics

- Oppotunity and risk
    - Definition of Opportunity: Possiblity of positive result player received
    - Definition of Risk: Possibilty of nagetive result player received
    - Co-existing

#### Example: Resource Management
  - Opportunity: 
    - Achieve a better goal under limited resources
    - By resource management, player can have a 1 + 1 > 2 effect
    - By making a correct choice, lose something to receive something
  
  - Risk:
    - Underestimate risk: Ingore the useful resources in the future
    - Upperestimate risk: Miss the important resources in current 
    - Can not get the best result when manageing resources 

#### Example: Anaylze Ability
  - Opportunity:
    - Understand the logic inside a game  to achieve a better effect
    - Predict the best movement which would affect future
    - Solve the puzzle in best way

  - Risk:
    - One step wrong, every step may be wrong 
    - Wrong choice may bring deathful damage
    - Use unnecessary, more resource to achieve better results

#### Example: Strategy (Long term)
  - Opportunity:
    - Faster than compititor 
    - Do th right choice in right time

  - Risk:
    - Misunderstand the info
    - Waste of time and resource
    - Bad strategy will ruin all the effect

#### Example: Tactic (Short term)
  - Opportunity 
    - Catch the fleeting chance to make correct decision 
    - Use the random result as a benifit
  - Risk:
    - Miss the timing may bring damagable result 

### CHOICE is the key of Player's MENTAL SKILL

### Define parameter to control choice

- The poportion of the right choice (Level of difficulty)
- The total number of choices player can make
- The contrast between different choices (Clearity to determine whether it is a right choice)
- The time limited allows player to make choice
  
  
# Game Programmer

## Education
- Game Programmer, Luleå University of Technology (2021-2024)
  * Additional Courses: Game Design, and Introduction to Artificial Intelligence.
- Network Technology, Mälardalens University (2018-2019)

## Work Experience
None in this field. Just came out of university in June 2024.

## Skills

### Proficient Programming Languages:
- **C++**

### Other Programming Languages:
- **C**
- **Python**
- **Angelscript**

### Game Engines & APIs:
- **Unreal Engine**
- **Unity**
- **OpenGL**

### Development Tools:
- **Visual Studio**
- **Visual Studio Code**
- **GitHub**
- **Perforce**
- **Helix Swarm**
- **Hansoft**
- **FL Studio**
- **RenderDoc**
- **CMake**

## Projects
### Bobby
<iframe width="560" height="315" src="https://www.youtube.com/embed/YKkjFaRAAGY" frameborder="0" allowfullscreen></iframe>

- **About**
  - "Bobby" is the result of six weeks of work from third-year game programming and art students at Luleå University of Technology (LTU). Bobby is a vertical slice of a stop-motion mystery game created in UE5 and is set in a small town, evocative of early 1900s London. The narrative centers on a bedridden girl whose sister has been missing for several weeks. Desperate to find her sister but unable to leave her bed, the girl imagines her favorite toy, Bobby the toy police officer, embarking on the search in her stead. Although Bobby isn't truly alive, he embodies the girl’s fervent hope that someone will find her sister.

    In the game, players control Bobby as he explores the town, gathering clues about the sister's disappearance. During his investigation, Bobby uncovers evidence of some kind of creature. Thinking that this creature might have something to do with the sister's disappearance, he follows the trail of clues in hope that he might uncover the truth.

- **My Role**
  - I primarily collaborated with a small team of two other programmers and closely worked with a group from the art team. Our task was to implement the town square, where the boss fight takes place, as well as the fight itself. The project was organized using sublevels, with the town square being one of them.

    **Boss and Minion Behavior:** I was responsible for creating the behavior for the boss and the slime minions that spawn during the fight. I implemented a finite-state machine (FSM) for this purpose.

    **Boss Behavior:** The boss had various attack states that it could choose from based on the distance and position of Bobby. Other states included popping up from manholes during the initial phase and moving between manholes.
**Minion Behavior:** The minions had simplified states compared to the boss, consisting of idle/wander, chase, and attack states.
**Boss System:** I developed a subsystem that mimicked the singleton pattern, known as the "boss system". This system was crucial for managing different phases of the boss fight and controlling the flow, such as determining the number of tentacles that would spawn at certain times.

    **Version Control and Code Review:** We used a combination of Perforce and Helix Swarm for storing project data and code review.
**Project Planning:** Hansoft was utilized for planning our tasks and milestones.
**Programming Language:** The project was programmed using Angelscript.
 
### Turn the Tide
<iframe width="560" height="315" src="https://www.youtube.com/embed/Czm_HKpNagA" frameborder="0" allowfullscreen></iframe>

- **About**
  - "Turn the Tide" was the first game I ever created during my first year at LTU. There were three other people that worked on it and we finished it within roughly four weeks. Turn the Tide is a two player, turn-based game focusing on strategy which takes place in the waters of caribbean. Control a pirate ship to naviage the waters and collect treassures which will reward them with power-ups in the form of cards to either aid them in battle or utility to cover the field more efficiently. The cards can be used in combination with the basic navigation to ensure you get in the perfect spot before using the power-up. The last one sailing wins!
 
- **My Role**
  - I was working on a bit of everything during this project. Implementing the movement, shooting, map generation, and some power ups. We worked using Github and Unity as our main tools, and just MS Paint for the UI art. The assets were not created by us, but downloaded from Kenney with the exception of the UI.

### Test Track
![Test Track GIF](https://user-images.githubusercontent.com/13751243/207295900-6bd38dcf-dff4-472a-9328-8066aaa0c0f9.gif)

- **About**
 - "Test Track" was made at the request of Colmis Proving Ground and was done alongside 4 other students at LTU using UE5. They wanted a realistic car simulator where one could test how it would feel to drive on one of their race tracks from the comfort of their home. To make it as realistic as possible, the map is a section of their own track and was 3D scanned and provided to us by the project owner. The final version we made was simply a base and took roughly 3 weeks, from which the project owner could then continue to work on.

- **My Role**
 - I contributed with the different type of weathers. The VFX particles were made using Niagara System and with the use of Blueprints, one can toggle between whatever weather they desire.

- OpenGL Graphics Engine [enter info].

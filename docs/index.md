# TDD

The technical design document contains the technical description of the production of a game. It contains all technology related items like software, hardware, engines or tools. It also contains a brief description of how this technology must be used.

The TDD is useful to communicate the technical details of the work to the team. It’s created in the pre-production phase and is updated in different stages of the production as the technical details are better defined or changed so there is usually a box on the first page containing a summary of changes

Laura Deng says that “while a GDD is derived from the game concept and is a functional description of the game from the user’s point of view, a TDD is an `architectural description` of the game from the `implementer’s point of view`”.

## Teachnical Goals

The technical goals are a list of objectives that define what is expected to be achieved `in relation to the code`. It can contain the game engine or the platform where the game is going to be delivered. Some examples would be immersive ambient sound, complex AI or realistic shadows.
	
`Example` A bomberman game running on a pc programmed with C++ and SDL. This game will have a functional player, bombs, enemies and some powerups (from project II)

## Technical risk

 A list of risks which must not be overlooked
 
## Code style Gidelines
 
Being one of the most important of the TDD, in this section are described the naming conventions that will be applied during the development of the whole project, in order to have an organized and homogeneous code that every programmer of the team is able both to understand and to work with. The thoroughness of the code style guidelines depends on the programming team and their objectives. Here are some examples of the elements one could find in this section:

Every #define must be in capital letters:
```
#define MAX_HP 300
```
Variables: using `upperCase`

Loops: using `while` instead of do while. When to use continue and break

Conditionals:
```
We prefer a conditional like if(something) {}
rather than one like if(something == true) {}
```
Clases and structs: organization and structure

XML
```
 If a node has just one attribute we'll declare it in the same line:
 <house colour="red"/>
```


## Resource Managment
In this section we detail all the types of files that will be included in the development process, their extensions, their maximum capacity and their characteristics. Moreover here is sett the files organization in the repository

![Image](https://github.com/avocadolau/TDD/blob/main/docs/Captura.JPG)

## Platforms Suported

It defines the target platform for which the game will be delivered, such as PC, Xbox, PS4 or other consoles. In addition, in this section is specified the minimum and the recommended hardware and software which are required to play it.

## CODE ORGANIZATION OVERVIEW (UML)

The UML offers a general outlook of the structure the code will have and the inheritance relation between its classes.
UML diagrams show the functions and the variables included in each module. It is a guide used to see the whole picture of the code. Nevertheless, this guide will change as the project goes by and the game evolves, becoming more complex each time and being extended with more specified UML diagrams of the emergent code modules.

![Image](https://github.com/avocadolau/TDD/blob/main/docs/generalUML.jpg)

## Branch workflow

Branches are very useful during the coding process of the game. It defines a series of rules and conventions that are going to be followed every time a member desires to make a commit. These rules consist of when should a developer branch, which branch should the developer use, when should the developer commit a merge and to which branch should the developer make the merge commit.

**Main branches**

Master: release production.

Develop : work to next release.


**Supporting Branches**

Feature : feature for a distant future release.

Release: all features for next release are finished.

Hotfix: to solve critical error in master version.

Code review: improving code without adding features


![Image](https://github.com/avocadolau/TDD/blob/main/docs/github-branches.jpg)

![Image](https://github.com/avocadolau/TDD/blob/main/docs/branches.jpg)

## Performance Budgets

Related with the technical goals, the performance budgets are a series of limits imposed on the metrics that affect the game performance. One the part of the performance budgets we define are the objective of FPS(frames per second) to which our game should go when we launch it to the market and how much time we spend as a maximum to the execution of different parts of the code (in ms). We can include a program to profile the FPS

![Image](https://github.com/avocadolau/TDD/blob/main/docs/brofilerImage.jpg)

[images well loaded](https://github.com/avocadolau/TDD/blob/main/docs/index.md)


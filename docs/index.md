## Welcome 

This web was made by  Xavier López([Xavierelm11](https://github.com/Xavierlm11) on GitHub),Spanish student of CITM,UPC, this is a personal research with the  objective of How to do a GUI for RPG.

### Introduction

In RPG games the UI is one of the most important elements to take into account when designing a videogame, since we will spend the whole game, especially in turn-based RPGs, navigating through the menus and analysing the information shown on the screen in order to act on it. We could say that they are menu games, so we must make the UI and menus as clear and comfortable as possible.

In this website we will learn how we should create an interface for the development of a game, what types there are, how to organise it, how to adapt it to gamepad, bad and good examples.

### Types of UI Menus

The first thing is not all games will have the same number of UI Menu types, it will depend on which ones are decided to be added and if they are necessary or not.
The most basic ones are (for most examples I will be using images from Persona 5 Royal):

- Main menu
(Persona 5 Royal)

![Persona 5 Main menu](https://user-images.githubusercontent.com/79161102/156952686-6025fec0-0800-42a0-8297-fda6e739a3a2.jpg)

(Pokemon White & Black)

![image](https://user-images.githubusercontent.com/79161102/156955947-209f974f-09ea-488d-be93-46f32682bc63.png)

- Options (Class Project)

![CP Options](https://user-images.githubusercontent.com/79161102/156953582-a76b9a8f-6a77-4366-9a1b-c276068e50f7.png)

- In game:
  - A save place(Persona 5 Royal)

![Persona 5 Royal_city](https://user-images.githubusercontent.com/79161102/156953757-5c61ffcf-c845-4c6b-95d3-7a2ce72c1ec7.jpg)

- A place with enemies, now we have mini map and state of each member of the party(Persona 5 Royal)

![Persona 5 Royal_20220304200122](https://user-images.githubusercontent.com/79161102/156954022-4cdef832-3c60-494f-8734-84796b713b06.jpg)
 
 - Dragon Quest IX (nds), due to the fact that the nds has 2 screens, it uses them to put minimap with your position.
 
 ![dq 9 in game](https://user-images.githubusercontent.com/79161102/156954347-5bac8bbf-b2a1-4cde-9b72-e0d56434b280.png)
  
  - Dark souls 3 (action-RPG), The only thing the UI shows us is basic information such as life, mana, stamina, tools, weapons that we can use immediately and the number of currency earned.
 
 ![Dark souls 3](https://user-images.githubusercontent.com/79161102/156954856-32fa3867-b227-4d24-a68c-edcf4d5fdfbf.png)
  
  - Death UI, a way to show the player clearly that he has died, how and why( Destiny 2)
  ![DEath](https://user-images.githubusercontent.com/79161102/156955211-f0a68ece-30fa-45c0-8608-13030b531e02.png)

  - Narrative boxes that shows us what the different characters are saying to us.
  
  (Persona 5 Royal)
  ![Persona 5 Royal_box](https://user-images.githubusercontent.com/79161102/156955423-15d95e0e-9475-479e-919b-9195ac95b645.jpg)
  
  (Pokemon Platimun)
  ![pokemon box](https://user-images.githubusercontent.com/79161102/156955548-8d0a8a07-9b9e-43c5-8e92-fb22216dbad6.png)

- Fast menu (optional)
(Persona 5 Royal)

![Persona 5 Royal_](https://user-images.githubusercontent.com/79161102/156955776-b695a401-890b-4b31-b43f-a3fd4ee4d27c.jpg)

(Pokemon White & Black)

![pokemon](https://user-images.githubusercontent.com/79161102/156955858-0910f485-288c-48a1-b204-9d3151977fc9.png)

Pokemon Heartgold/Soulsilver uses the tactile screen as a fast menu

![image](https://user-images.githubusercontent.com/79161102/156956418-1d12344e-c1fe-4eef-8631-52955487cf15.png)

- Pause menu, shows all the options the players can access to get organised/customise/customise/analyse/view stats/save/load/go to options, It is very important for the player to see which option he/she/they is constantly preselecting.

(Persona 5 royal)

![Persona 5 Royal_20220304193312](https://user-images.githubusercontent.com/79161102/156956765-822dde08-7d69-41c0-866c-dbb6f939e558.jpg)

(Dragon Quest XI)

![image](https://user-images.githubusercontent.com/79161102/156957011-c6bcbb90-89e0-4a43-aa92-287c3a13343e.png)

(Pokemon Platinum)

![image](https://user-images.githubusercontent.com/79161102/156957319-d8604f81-857c-48b0-82ba-79d36476abf6.png)

(Pokemon White & Black), we are clearly shown the type of attack it is, the number of uses we have left and the stats of our Pokemon (who will fight).

![image](https://user-images.githubusercontent.com/79161102/156957813-71f4978a-26f5-4c0e-a278-b6bab0efb4d1.png)

(Destiny 2), if we are going to have equipment it is important that each piece is organised with its category and if we are going to have rarities it is important to use a colour system that the player can recognise quickly and that is similar to other games.

![image](https://user-images.githubusercontent.com/79161102/156958248-9954b2cb-2c52-4a34-ac00-251a53d97a97.png)

(Fortnite rarities), from worst to best, the color system more used

![image](https://user-images.githubusercontent.com/79161102/156958328-4bfa4a33-69be-4836-9df9-52a0b83819bb.png)

- Map (optional), is not necessary and how you want to display the information on the map is entirely variable depending on what design decisions you make, but if you are going to include icons you should clearly show what they indicate.

(World map Persona 5)

![Persona 5 Royal](https://user-images.githubusercontent.com/79161102/156957569-ad15177b-7333-4253-b352-7640105bb2a0.jpg)

(Zone Map Persona 5)

![Persona 5 Royal_](https://user-images.githubusercontent.com/79161102/156957717-e9103d4d-ff16-450d-9060-bb93bb4c7778.jpg)



- In combat, the best possible use is made of the space available to show in the clearest and simplest way what is happening in combat, the state of our party and what we are doing. To show different life/mana/stamina bars .... we usually use complementary colours or colours that can be differentiated at a quick glance.

(Dragon quest XI)

![image](https://user-images.githubusercontent.com/79161102/156958986-98a5852e-6f4a-4a7b-9e26-3d0fc8499364.png)

(Dragon quest IX)

![image](https://user-images.githubusercontent.com/79161102/156959328-dba81c33-74e7-4821-b56e-815b09f5ac09.png)


(Persona 5 Royal)

![Persona 5 Royal_20220304202138](https://user-images.githubusercontent.com/79161102/156959064-29ac0247-9ee9-4b97-a568-ae69f40abde6.jpg)

if something different happens during the combat like a special attack or a critical hit it should also be shown, in most of the current RPGs they usually show the affected damage, enemies, allies and their life bar. 

![Persona 5 Royal_20220304202506](https://user-images.githubusercontent.com/79161102/156959622-46eb049b-eea1-4e3c-a7a5-aaea0258a504.jpg)

![image](https://user-images.githubusercontent.com/79161102/156959703-e55cd87f-ba11-41be-8029-c44daf784e96.png)

it is also necessary at the end of a combat if we have obtained any reward or xp. 

![Persona 5 Royal_20220304203503](https://user-images.githubusercontent.com/79161102/156960356-0effe037-c993-45a2-a727-834963ec930e.jpg)


(Pokemon Heartgold)

![image](https://user-images.githubusercontent.com/79161102/156959393-c8f59a22-3c95-4601-85e2-53252d9e50cf.png)

(Final fantasy VII Remake)

![image](https://user-images.githubusercontent.com/79161102/156959521-7519dde1-6cd8-4a9e-9405-41e63247b707.png)

(Dark souls III)

![image](https://user-images.githubusercontent.com/79161102/156960471-0a2e7283-f158-4eae-91f5-692bab9ec2da.png)

### User experience

In Pokémon platinum, when we talk, we are never shown who we are talking to, contrary to what Persona 5 previously showed.

![image](https://user-images.githubusercontent.com/79161102/156961044-cacbde12-083e-472e-ab5f-e699a60463b3.png)

In final fantasy 2 the information shown to us is CHAOS, we don't know what any number or name is, all the letters are the same colour and there is no nomenclature or symbol to tell us what it means.

![image](https://user-images.githubusercontent.com/79161102/156961277-9bfac4db-0e12-49ce-8714-06c6c280d8f2.png)

### For our development

When creating UI Menus it is important to start with a quick sketch of each one, but first we will make an outline to see what elements we have and have to show in some way, and nothing happens if we have no idea how to make a UI, we can look for examples and adapt it to our needs.

Outline of Main menu

![Group 1](https://user-images.githubusercontent.com/79161102/156962010-7a148a79-ca30-4973-8ff7-fb544f17eda3.png)

Diferents Sketchs of main menu distribution

![START2](https://user-images.githubusercontent.com/79161102/156962101-48ed0fa7-51be-42ea-b9ee-c070a6612087.png)

![START](https://user-images.githubusercontent.com/79161102/156962122-23ab5d27-13a2-4dea-a324-91fa75c28f2e.PNG)

![start4](https://user-images.githubusercontent.com/79161102/156962141-bb63b51c-7c1c-4243-9d21-64a8b622071b.png)

![STRT3](https://user-images.githubusercontent.com/79161102/156962172-c33b7803-c574-4ee5-a248-ac0d815d8a69.png)

Outline of Options

![CONFIG](https://user-images.githubusercontent.com/79161102/156962258-94b8fc1a-04e6-4303-95d3-719e3a052eb6.png)

Exemple combat UI of game that we are developing

![image](https://user-images.githubusercontent.com/79161102/156965311-56a09dd4-f61e-49b1-98cc-db5049ff6d4e.png)


### Using Gamepad in menus

In some ways it is much simpler than it seems, the clearest example is Persona 5, where we are constantly shown discreetly on the bottom edge of the screen which action each button performs, and by not using the mouse, which has more precision, we must indicate which option the player is preselecting.

![Persona 5 Royal_20220304193251](https://user-images.githubusercontent.com/79161102/156962658-31256862-237e-490c-a03e-629286f51df2.jpg)

(Dragon quest XI)

![image](https://user-images.githubusercontent.com/79161102/156962715-45335bd8-2e7d-48eb-a815-134c6304a8a2.png)

### Interesting video (Spanish)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Yx1bPmeo6L8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Links

- https://www.youtube.com/watch?v=Yx1bPmeo6L8&t=18s&ab_channel=Joseju (video)
- https://interfaceingame.com/ (web to see UI of games)
- https://github.com/alexgesti/Odd-Space/wiki/GUI-Design-Document#credits-screen 
- https://mitarn.wordpress.com/2010/05/20/dragon-quest-ix-why-torment-me-so/
- https://finalfantasy.fandom.com/es/wiki/Final_Fantasy_II  
- http://www.destinorpg.es/2018/10/la-gestion-de-menus-en-el-genero-rpg.html
- http://desmume.org/ (Emulator used to play some games)

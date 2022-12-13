# OAISIS

## Introduction
The purpose of this application is to address the problem of low interaction on the present e-commerce websites. Most of the time, users can’t get a real feel for buying things because of the low-quality images on the website and missing information. Our application gives the user access to interact with others in the metaverse. They can play games, interact with human avatars, grab objects, and walk around the shops and restaurants.

### The Platform
Our platform gives users access to a virtual world of entertainment facilities from the comfort of their homes, avoiding the problem of having to go outside. Users can use the car to access the main menu to play the game. When they start playing the game, soft music in the background starts playing. The user can walk on the road or explore the full city. They can visit the shop and grab objects such as cups, food, and other things available there. We have also created the indoor design of the restaurant, where they can grab the real food and then decide to order it online. A normal food delivery website uses images of the food, but our website has interactive 3D food like the real world, which can be grabbed by the user, and they can know about the information from there, like the real world in the virtual world. At the end when the user wants to exit the game they can come back to the car, where there is the main menu and they can exit the game by pressing the exit button.

### Inspiration
Metaverse means a 3D virtual space similar to the real world where users can interact with the computer-generated environment. E-commerce is a sector that will impact the metaverse more than anything else. In the present world, Coca-Cola and Samsung are already using virtual billboards within video games like Football Manager and Hyper Scape. Gucci sold its $4000 digital bag on Roblox. Other popular bands, like Balenciaga, are collaborating with Fortnite to create virtual outfits, accessories, and weapons that players can buy for their avatars.
Inspired by these, we planned on creating a game where users can do all of these things, but it is also going to be a space for the users to spend time with their friends. We planned on using Mixamo.com’s 3D avatars for users to select their avatar. One of the goals was to build a login system that can be used by users to log in from any device, and their information will be saved on our server. also providing the companies with a space for their shops. As we don’t have a server right now, we decided to develop this feature in the future.

## Development
This project is built primarily on the Unity engine, with use of Visual Studio for the scripts utilized in the game. We have used a free open source music library for the background music. We have imported different assets but we have customized all of them before using them in our project. We have used blender for some of the 3D models in our project.

For now we have two options , one is for playing games and the other one is for exiting the game. When the user selects the “Play Game” button it changes the scene and takes the user to the OASIS, which is our demo environment for shopping malls and restaurants for this project.

The project will start with a menu scene where users are sitting in a car, the menu prompts users to choose either playing the game and entering the main scene or exit. Also, the project gives users freedom to walk around the metaverse, and the users are able to use controllers to make something happen, such as interacting with the objects, grabbing a cup of coffee or a key etc. Also, considering the boundary problems, we created four invisible cubes on each side of our metaverse, so that the user would not be able to fall off the boundary. Furthermore, considering the users would be able to get on the sidewalk, we also created a cube which covered the whole metaverse, so that users are able to do that. 

## Known Bugs
While using the Plastic SCM,we faced the issue in changing one scene and uploading it from two different computers to the cloud. We also faced issues while changing the code for different assets that we imported from unity.But at the end with the help of our instructors we were able fix the bugs

There were few issues with the alignment of text and objects in the game. We tried to fix the alignment. Right now if the user sits in a chair he can see the menu in the right position.  We also added an NPC (Non-Player Character). Our aim was to make these NPC movable inside the metaverse. So that when the user goes inside the game he doesn’t feel alone. He can interact with the NPC and if he clicks a button he can talk with them. In the beginning of our project the NPC were moving in the scene  view but not in the game view.We  are still working on figuring out how to best address this problem.

## Future Implementations
- Login And User Menu to select characters: The same way every user has a unique ID, they will also have a unique avatar. For this, we will be using Unity assets and C# code to help the user change their character.
- A big server for giving service provider (eg Amazon, Gucci, other companies) space for showcasing their product
- When the user grabs an object eg. cloths, food  it will automatically pop up a small window to show them details like the price, materials, date of expiry etc
- Two users can interact with each other at the same time by using our game

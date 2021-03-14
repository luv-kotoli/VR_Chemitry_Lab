# VR_Chemitry_Lab
### CS5188 Course Project
### First Part

**This is a project build with Unreal Engine 4.26 and started from the VR Templete.**
**The teleport function has been implemented in the templete, so that's not our work.**

## 1.Launch Environment
1. This project is build for VR project, so **a complete set of oculus Rift** is needed.
2. This is the source code and project, so the **Unreal Engine 4.26** is needed in your computer.
3. To launch the oculus Rift, Oculus Software is needed and a computer with **compatible graphics card**. Detailed information can see this webset [Oculus Rift](https://support.oculus.com/326247701060681/).

## 2. Contribution
Our target of this project is to build a VR Chemistry Lab. The main contribution in the first submission is on implementing some small fuction. It include 
1.  Build a Pariodic model in 3DS Max and put it into the UE Scene. The origion model is in `Content-> Periodic_Table` and `Content-> Periodic_Elem`.
2.  Add button to each element and show a detailed information picture in the next screen. (Now only the 1st and 11st Element Implemented for test). Each click has a click sound played. 
3.  Add a music playing menu in the scene. It has 3 buttons which can set a music to play, pasue and stop. It has only one test music in the project and we will complete it in the final submission with more functions of playing music and if possible, play some Chemistry Experiment Viedos. Detailed blueprint can be seen in `Content->Model->Micheal`
4.  There are now 9 lights in the scene. 4 to the periodic table and the other 5 on the wall. At first, we use a collision box to detecte whether the user is in the collision area. If the player is inside, all the light will open, otherwise, only one light will be left opening. However it may not work well in this version after some change in our code. The blueprint of this part can be seen in `level blueprint`
5.  We add a popup menu near the player, if you use the B button in your right oculus touch, it will appear and disappear. There are 4 buttons on the menu, two can control the light open and close and the other two can change the color of light near the periodic table. Detailed buleprint also in the `level blueprint`.
6.  When you start playing, there will be two beams shoted out from your hand, and you can use the beam in right hand to do some interaction with some widgets. Use the grip button on Oculus Touch to press button. This part blueprint is in `VirtualRealityBP->Blueprints->MotionControllerPawn`.
7.  Almost all of the work of us can be find in `Model` fold and the `Level Blueprint`. Detailed division of labor is shown in our document.

## 3. Launch
**Use the clone to get the project. If you use the button 'download zip' to get it, there may be some error when you open the project**
After upzip, double click the `VR_Chemistry_Lab.uproject` can enter the UE Editor and you can use the preview in VR to test the functions.



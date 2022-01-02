# Solar System
 
This was my project from the 12th semester of course Computer Graphics and Multimedia.

Our project is based on Solar System. Basically The solar system is the sun and everything that orbits around it. It includes the planets and their moons as well as numerous asteroids and comets. These objects are all held in orbit around the sun by the sun's strong gravity. In our Project we have included the planets according to thier orbit. By giving the necessary functions we try to bring the real graphical interface which shows the natural look of our solar system and by observing this anyone can get knowledge about the 3d View of our solar system and it can be used for educational purposes.

---

## Simple explanation of code

Now I will explain the code. 

First of all we define the angle of rotation for the camera, direction and Position of the camera according to viewpoint. 

Then We have taken function Call drawStar.
In which we set the star color White, included function glBegin and glend functions to delimit the vertices. This function accepts  argument in our function. 

Then we set the light according to the surrounding graphical interface and set the lighting position. This will help us to easily setup the solar system planets color. 

Afterthat  we draw the solar system 
In which we include our all the planet color by calling the function and then transtalting the values. Also included function glutSolidSpeher this Renders a sphere centered at the modeling coordinates origin of the specified radius.  

Then we have taken  function called void renderScene in Which we set The gluLookAt function which defines the viewing transformation. Under this section we also add conditions to draw the solar and Star. 

Then we call a function void processSpecialKeys this will set the special keyboard callback for the current window. The special keyboard callback is triggered when keyboard function or directional keys are pressed. We use Switch case statement to implement it and include break statement at Bottom. 

Afterthat we include function void changeSize to set the Window size and given our window ration as needed to our requirement. 


Afterthat we have Taken function to setting up our key value which Include the conditions when to exit the program. 


At the very last we work on our main function 
This initialize the graphic window, register the callbacks to display our project and completes the whole event processing circle. 

That's all about my project. By working on this project I learned a lot. Thank you!

---


# Youtube Link
Click on the link below to get a good explanation of the code and to understand it better.

https://youtu.be/bettCwYlq-A

## How to install and run my project on your local system

- Clone the repository with git clone https://github.com/JHS-Sujel/SolarSystem
- Intall codeblocks or dev c++ 
- Setup freeglut on your program ( Youtube link; for CodeBlocks https://www.youtube.com/watch?v=4-SkG5Xh5ME & Dev C++ https://www.youtube.com/watch?v=8Qkpaewj-7Y ) 
- Open project (Solar System.cbp file)
- Then Run
---

## License

Basically, feel free to use and re-use any way you want.

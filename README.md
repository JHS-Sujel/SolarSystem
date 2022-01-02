# Solar System
 
This was my project from the 12th semester of course Computer Graphics and Multimedia.

Our project is based on Solar System. Basically The solar system is the sun and everything that orbits around it. It includes the planets and their moons as well as numerous asteroids and comets. These objects are all held in orbit around the sun by the sun's strong gravity. In our Project we have included the planets according to thier orbit. By giving the necessary functions we try to bring the real graphical interface which shows the natural look of our solar system and by observing this anyone can get knowledge about the 3d View of our solar system and it can be used for educational purposes.

---
## About function 

*void drawStar() and void drawSolar()

glColor3f(): Can be called in between glBegin and glEnd, when it is used this way. It can be used to give each vertex its own color. The resulting rectangle is then shaded with an attractive color gradient.

glVertex3f(): It has three floating point, which is considered as x,y and z. It determines where the vertex is in space.

glutSwapBuffers(): glutSwapBuffers swaps the buffers of the current window if double buffered. Performs a buffer swap on the layer in use for the current window. Specifically, glutSwapBuffers promotes the contents of the back buffer of the layer in use of the current window to become the contents of the front buffer.

glEnable(): It enable to plug in colors you want to enter in it.

glLightfv(): The glLightfv function sets the value or values of individual light source parameters.

glTranslatef(): The glTranslatef function multiplies the current matrix by a translation matrix.

glutSolidSphere(): The glutSolidSphere() function draws a shaded sphere centered at the origin. The surface is created from quadrangles (except for triangles as degenerate quads at the poles) in a longitude/latitude pattern. The equatorial great circle lies in the xy-plane and is centered on the origin.

glRotatef(): The glRotatef function computes a matrix that performs a counterclockwise rotation of angle degrees about the vector from the origin through the point (x, y, z). 

---

*void renderScene(void)

glClear(): Clear Color and Depth Buffers

glLoadIdentity(): Reset transformations

gluLookAt(): Set the camera

glPushMatrix() and glPopMatrix(): Used for push and pop the current matrix stack

for loop(): Using for draw a solar and star 

---

*void processSpecialKeys()

Using switch case statement to implement it and include break statement at bottom

---

*void changeSize()

Using for windows size

glMatrixMode(): Use the Projection Matrix

glLoadIdentity(): Reset Matrix

glViewport(): Set the viewport to be the entire window

gluPerspective(): Set the correct perspective

glMatrixMode(): Get Back to the Modelview

---

*void processNormalKeys()

When to exit the program

---

*int main()

It's a callback function, callback function called when even occurs. This functionis used to callback all the above function 

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

Now i will run my project 

The first appearance is animation of planet movement, they move around the sun automatically, and it also give general information about the solar system.

https://user-images.githubusercontent.com/73945266/147878964-7e1cf164-3edc-481d-b58f-978a19157113.mp4

That's all about my project. By working on this project I learned a lot. Thank you!

---

## Tools Stack
- Language: C++
- IDE: CodeBlocks
- Library: Glut, freeglut, OpenGL

## Youtube Link
Click on the link below to get a good explanation of the code and to understand it better.

https://youtu.be/bettCwYlq-A

## How to install and run my project on your local system

- Clone the repository with git clone https://github.com/JHS-Sujel/SolarSystem
- Intall codeblocks or dev c++ 
- Setup freeglut on your program ( Youtube link; for CodeBlocks https://www.youtube.com/watch?v=4-SkG5Xh5ME & Dev C++ https://www.youtube.com/watch?v=8Qkpaewj-7Y ) 
- Open project (Solar System.cbp file)
- Then Run

The rotation of the planets around the sun
![Screenshot (517)](https://user-images.githubusercontent.com/73945266/147875979-c2bd6c57-0947-41ca-8188-e9b6371bc10b.png)
---

After that; if you have any query then you can email me:  jabedhossainsujel79@gmail.com 

---

## Author
Name: Md. Jabed Hossain Sujel
ID: 181-115-034
Dept. of CSE
Metropolitan University, Sylhet

##Project Supervisor
Name: Masum Ahmed Eesha 
Lecturer
Dept. of CSE
Metropolitan University, Sylhet

## License

Basically, feel free to use and re-use any way you want.

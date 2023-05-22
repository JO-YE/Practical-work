# Research & Project approval (Part 1)

## Concepts
- [Maze Project](https://intranet.alxswe.com/concepts/133)
```
The goal of this project is to create a game in 3D using raycasting !

You don’t have to do the tasks in order, except for the first one (obviously), or if a task depends on a previous one

You have a link to a very good and very long tutorial about raycasting in the Tips and links section below, so read it very carefully, and practice !

Please have a lot of fun doing this project !
```
- ![img](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/8970c3ee63d8149b93e30229276c3f7580ac9447.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9a49c9797108004aa9280384f6c261571674c14f995bbb1200d19e22ec36e17c)

- [SDL2-get started](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/1/9da3b82dc0bcfea07858b70956de47f0e2db2dad.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T155051Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fa3dbedd7e0343695783e0d16692c6f4c4b04556ec9ddfea71a9ced9840a606c)

- [SDL2 tutorials](https://lazyfoo.net/tutorials/SDL/index.php)
- [RAYCASTING](https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- Be careful with tutorials/help online: We are using SDL2, and not SDL-1.2 !
- [Alternative Raycasting](https://lodev.org/cgtutor/raycasting.html)

## Important
- Don’t forget to install SDL2 [SDL2 tutorials](https://lazyfoo.net/tutorials/SDL/index.php)
- There are no forbidden functions for this project. You are allowed to use any system call and/or standard library function.
- You are allowed to use [all the functions provided by SDL2](https://wiki.libsdl.org/SDL2/CategoryAPI)

## Tasks
0. Walls!
> In this first part, you’ll have to:
>
> Create a window with SDL2
> Use raycasting to draw walls on your window !
> You don’t need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it
> The color of the walls must be different from the color of the ground/ceil
> The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters).
- example
- ![img2](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/7e897a79ffe0d990856e021f4e1e6cdbb0ff5395.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=97c69809ec46ab486e6ad913dfc3ba6693bdd145a1870dbd580c281fe1060b48)
> In the following image, the camera is the red square, and the visible area is painted in green:


1. Orientation
> In this part, you must draw a different color depending on the orientation of the walls.
>
> You must at least draw walls facing NORTH and SOUTH in a different color from walls facing EAST and WEST.
> 
- ![example](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/bc20224777aa01d6b9b6f6944421beb1850fecb6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=92d3826f683e21049f3ed367d6fd5a14b382e1db38704634dea58bc6b734bc2d)

2. Rotation
> You must provide a way to rotate the camera during the execution.
>
> For example, you can rotate the camera when the left,right arrows are pressed on the keyboard.
> Or you can rotate the camera when the mouse moves, just like a FPS game !
- ![exa](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/7e322c5b857225f95fcf63795f5d68f954ab4474.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b5dfd7c2d5cb4e3ba11201fe285fdafe4f808f06e6f33685198359ff94299681)

3. Move
> You must provide a way to move the camera during the execution.
>
> For example, you can move the camera when the w,a,s,d keys are pressed on the keyboard.
- ![exam](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/410f88f83b1de01b8fc2349d6c89a2743ba933a6.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cca07db088fb656a96b42313cbe9932704156ea419113a57358f61846f5b5a82)
- ![exam2](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/491510b693b38cf88f0d6e8917f6dc467e507635.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9d75e0c9c2e6086c5097b0fa23b589abdcbf6e33aeebd57ec1456b1d3849b201)

4. Ouch !
> In this part, you must handle the collisions of the player (yes, let’s call the camera player now, it’s getting serious) with the walls.
>
> The player must not be able to enter walls
> You can make the player slide on the walls instead of just stop it.

5. Parser
> In this part you must implement a parser to get the map from a file.
>
> You are free to define the standards of your map (The character for a wall, the character for nothing, the extension of the file if you want, …)
>
> Your program will need a parameter to run which will be the path to the map file

6. Draw the map 
> In this part, you must draw the map on the window.
> 
> You’re free to draw the map where you want, with the color you want, …
>
> You must provide a way to enable/disable it during the execution
>
> Include the player’s line of sight in the map

7. Coding style + Documentation
> Check if you code fits the [Holberton School coding style.](https://github.com/holbertonschool/Betty/wiki)
>
> Check if your code is well documented and respect the [Holberton School documentation format](https://github.com/holbertonschool/Betty/blob/master/kernel-doc.pl)
>
> You can check all of this by yourself, just follow the instructions on [this repository](https://github.com/holbertonschool/Betty)
>
> The check will be done on each file present on your turn in repository. Even the files that was not required. So don’t forget to always keep your turn in directory clean.
>
> Be careful

8. Textures
> In this part you have to add textures on your walls!
- ![imgg](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/c6106183de275a10df8994437f710118ee59d654.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=12fa6983d735ed43e33f27c8dcf47732c5c8b49c2a56f811dae99ca7a2cca19a)

9. Multi task !
> Add a way to move on several directions and rotate in the same time. Basically in this part you’ll have to handle multiple events on the same frame.
>
> For example, if the keys to move are w,a,s,d:
>
> If the keys w and s are pressed in the same time, the player shouldn’t move.
>
> If the keys w and d are pressed in the same time, the player should move forward and right in the same time.

10. Ground textures
In this part you have to add textures on the ground and/or on the ceiling !
- ![imag](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/87792f3b4d787bf589befb8611de67a4f04d44c0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3a8d0a53b87c95bc11292b245ce1e07914d227f9698b66225d88f03294aac70c)
- ![t10](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/bc961dcd5fb040c7ba1c3d7f5c640acdc2b04a34.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d3f674de377467570b92a5935c7cf9f2fa31cdbac502ba45f668330e177acf63)

11. Weapons
> Add weapons textures !
>
- ![wea](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/9e1e52c573a2cfb6639b0d364d0ab59ad35ab242.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9306ab89993dd73bb89466710e2d7ce7bdd98b5c1bfd830172dde7b499868c12)

12. Enemies
> Add some enemies !
>
> Example from the game Wolfenstein 3D:
- ![enemies](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/d24c48be8c7ee901d251f35cad5673705d4dcc70.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T152925Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a51d40981f2d7a8ef08589e074cb3479f557bd978bd3b75eeb855a36cc3e226c)

13. Make it rain
> Add rain and a possibility to stop / start the rain with a key.

14. Extra option
> Shadows, special lightning, etc… get creative!


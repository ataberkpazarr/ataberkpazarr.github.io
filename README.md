

# Unity Projects

### [Project 1: Row-match 2D game](https://github.com/ataberkpazarr/Row-Match-type-2D-Puzzle-Game)

Row-match game with 10 levels. Like candy crush but player only gets point if he/she makes 
same colour all row. For etc. İf all row elements are green then player gets points with respected to its colour and the row 
locked and that row’s elements become unmoveable. Highest scores are set to 1000 from default and if user finishes the 
level with a score higher than 1000, then the new level is being opened. Developed and specified the game by watching an 
[Udemy course](https://www.udemy.com/course/make-a-puzzle-match-game-in-unity/) .
All the levels takes places in the same scene with changing width, height etc. configurations. 

![resim](https://user-images.githubusercontent.com/55497058/134746670-5bf0750b-8fd0-4552-ae76-fccfb7d66fd5.png)




### [Project 2: CubeSurfer 3D](https://github.com/ataberkpazarr/CubeSurfer3D)

CubeSurfer3D is famous game of Voodoo Studio’s. It is avaliable for both Android 
and IOS. I had tried to make clone of it.  I only implemented 3 levels. For the sake of development, it is not in 9:16 
resolutions, it is in 16:9 resolutions, that’s why the below screenshots are seems wide. In the game, the main 
player may collect the red cubes, and increase its size, may take from coin and increase its stored coin(right up 
corner), may collide an obstacle and it can lose size with respected to collided object’s size, and also we are 
able to see the way that player took in the above of screen (180). 

![resim](https://user-images.githubusercontent.com/55497058/134747121-45ab7023-a575-4c7d-9c7d-064844adc996.png)
![resim](https://user-images.githubusercontent.com/55497058/134747137-653eac56-120e-43b7-89c5-baaed401cc3b.png)





### [Project 3: Motorcade Guard Game 3D](https://github.com/ataberkpazarr/Motorcade-Guard-Unity-Project) 

3D Traffic Racer type of a game. Bunch of different cars can be selected by the 
player. Player moves in 9-lined highway with his/her selected car. The main car has 6 guards (hummer type of 
jeeps) in its around and whenever a car in the traffic collides to the convoy, one guard car is being destroyed. Gets
harder in next levels by making highway traffic more crowded. The main skeleton of the game is taken by this [playlist](https://www.youtube.com/watch?v=iXa0riFpWGQ) and customized then.

![resim](https://user-images.githubusercontent.com/55497058/134747565-a8ffa103-d3c6-46d9-bed3-7931542c995a.png)

### Project 4: Shorty Climb Clone 3D

Tried to implement clone game of ShortyClimb. Character moves between 
surfaces and whenever it goes outside of the surface, the carried steps are started to consumed and being 
instantiated in the locations where user walks. The main logic in moving as following; character is moving ahead 
by default with a constant velocity and the direction of the character depends on the user mouse input, 
wherever user drags mouse character goes towards that direction. For implementing this behaviour I found a 
free joystick package in Unity and embed joystick as GameObject to the scene. Joystick gameobject gets active 
whenever user click with mouse and deactivated whenever user release the mouse but it never being seen by 
user (invisible in gameplay but exists in below screenshots). But going back movement is not stabilized thus I deactivated it and also the repo exists in my 
Github as well as the other games, but this one is in private repo.

![resim](https://user-images.githubusercontent.com/55497058/134748132-87f9beb4-dd64-49e6-aa88-065375503f51.png)

### [Project 5: StackyDash Clone 3D](https://github.com/ataberkpazarr/Stacky-Dash-Clone) 

In this project, I tried to make a clone of StackyDash mobile game which is avaliable in 
Ios and Android. I implemented 3 levels and game mechanics. Also I used a free Unity plugin which is called Path Creator 
for having S-shaped (curve shaped) paths. Most noticable thing about this project is and the projects after this one, previous ones, that I 
did, had been done when I was actively working in Vestel. Thus I was not able to fully focus on projects so they had lots 
of bugs. But starting from this one, bugs are minimalized and the codes are much more qualified in compare to previous ones.

![resim](https://user-images.githubusercontent.com/55497058/134748662-1627ab29-d531-4535-aa67-1797bf064e13.png)

### [Project 6: Tower Defence 2D](https://github.com/ataberkpazarr/Tower-Defence-2D)

In this project, I tried to develop a similar game to Rooster Defense game which is a famous tower defence game. As a skeleton I watched and 
finished the [Udemy course](https://www.udemy.com/course/learn-how-to-create-a-2d-tower-defense-game-in-unity-2020) and then changed lots of things to make it similar to Rooster Defense game. Since it is a 2D game which covers the screen, below screenshots are wide and not in classical mobile game resolution.

The game mechanics are as following:

At the end of every wave, enemy’s initial healths , spawning a new turret cost and earning per kill to 
player(relatively small increase ), are being increased. If the wave can not be completed, game reload 
the same wave. Turrets are permanent and being saved with their levels and locations. When game 
is exitted and started again, previous game’s turrets are being loaded at saved locations with saved 
amount of coins. Also There is a delete Player Prefs button at the game, if its pressed, all saved player 
prefs are being resetted and game is being restarted. In the turret upgrade operation, whenever user 
selectes a turret by mouse, a pop-up emerges with options of Destroy/Upgrade if upgrade is being 
selected then it is being checked if any possible match exists with same type of turret, if it exists then 
selected one upgraded at the same node whereas other one is destroyed.

![resim](https://user-images.githubusercontent.com/55497058/134749031-fce78c63-4bc9-4822-8f2c-0858f45dac60.png)
![resim](https://user-images.githubusercontent.com/55497058/134749090-e86f4a8a-6317-4eaa-af68-df1d352363d2.png)
![resim](https://user-images.githubusercontent.com/55497058/134749153-9b51a756-3566-4302-a96e-93ac04844d4a.png)
![resim](https://user-images.githubusercontent.com/55497058/134749178-2468de7a-7d01-442d-a2f5-6a042000aa5b.png)

### [Project 7: Walking Shooter 3D](https://github.com/ataberkpazarr/walking-Shooter-3D)

This project can not be classified as finished game but it is a trial for myself. I used some new mechanics and features that I have not experienced before.

I used New Unity Input System and a brand new Third Person Character Controller Package. In this project a character walks through the area which it exists by W-A-S-D controllers, runs when pressed shift and jumps with space, aims with right click and shoots with left click.

<img width="483" alt="Resim1" src="https://user-images.githubusercontent.com/55497058/147158099-8345f91b-5fed-4e0e-9ddb-255a712f64af.png">

<img width="454" alt="Resim2" src="https://user-images.githubusercontent.com/55497058/147158120-1edb8bf9-aa57-444c-ae58-2a98463fc9d2.png">




# Other Github Projects

### [Project 1: AWS-Websocket-Chat-Application](https://github.com/ataberkpazarr/AWS-Websocket-Chat-Application)

Developed an web-socket real time chat application architecture with AWS Lambda, Websocket API Gateway and DynamoDB. Also nodeJs and Python is used

![resim](https://user-images.githubusercontent.com/55497058/134750264-339e73ad-e574-4e96-a1e6-5eff34694489.png)

### [Project 2: Mask Detection Webcam App](https://github.com/ataberkpazarr/Mask-Detection-Webcam-App---Python)

A program, using machine learning, which decides if the person, in webcam's view, wears a mask or not. Very detailed information is on the link that embedded on the header.

![resim](https://user-images.githubusercontent.com/55497058/134750594-c9d75377-6cc9-4161-aa4f-0a3271d65280.png)


# Undergraduate Projects

## Group Projects:

### Graduation Project
Aimed to create an ampihibious autonomous vehicle, due to Covid-19 it is half finished. I handled with computer vision and CV-Image Processing related algorithms. 
### Machine Learning Course (CS412) 
Used Adaboost, implementing it with Python, in Google Colab. Created a model that  assumes if a customer will pay its credit debt in future, used data had 700.000 rows and 60 columns. 
### Cyber Security Course (CS432)
Cryptographic signatures, encryption, decryption implementations for secure communication between server and multi clients with using C#. 
### Cryptography Course (CS411) 
Implementing digital signature for blockchain transactions, implementing proof of work (POW) and creating blockhain with using elliptic curve digital signature algorithm (ECDSA) with C#. 
### Software Engineering Course (CS308)
Implementing E-Commerce web-site, dealing with front-end back-end parts, with C#, Vue, Amazon online database. 
### Internet Protocols Course (CS408)
Implementation of server- multi client connections and other challenging specifications like observing the traffic by server etc, C# used. 
### Mobile Application Course (CS310) 
Android Studio project which was about developing a mobile application to Android  Studio. Developed a fitness-diet application. 
### DBMS Course (CS306) 
Developing basic web-site including a relational database, with using Sql, PHP, HTML. 

## Self Projects:
### Operating System Course (CS308): 
Developing a desktop program which was about simuliation of an OS, including insturments of OS like cache etc, with using Java. 
### Physical Computing Course (VA455): 
Ardunio and Python involved project, which determines if the person in computer’s vision wears a medical mask or not. 
### Logic-system Course (CS303): 
Self-project by using Xlinx. 
### Data Science Course (CS210):
About the positive correlation between the World Happiness Index and GDP per capita with usage of python.

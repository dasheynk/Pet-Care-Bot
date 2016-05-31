# Pet Care Bot
Majority of pets are left home alone and have no one to interact with. They can become  bored, depressed, or even disruptive. This robot will act like a care-taker for the pet so that the animal will finally have a companion while you are away. As of right now, the robot is able to 'see' the pet through the raspberry pi camera and from there follow the pet around the house. Pet owners can even use their phone to connect to the camera and see what the pet is doing. New features will be added in the future such as pet feeder and a speaker for voice interaction. 

# Installation
### Configure the Raspberry Pi for OpenCV
1) Download the Raspbian that can be found on the raspberry pi [website](https://www.raspberrypi.org/downloads/). I recommend using a 32GB microSD card.<br />
2) Once the Raspberry Pi is set up, connect it to a monitor that you have at home.<br />
3) Once all that is done, open the terminal and enter the following commands before installing OpenCV:
 ```
 sudo apt-get update
 sudo apt-get upgrade
 ```
### Installing OpenCV
Now we need to install OpenCV. Open up the terminal and type the following command:
`sudo apt-get install python-opencv`


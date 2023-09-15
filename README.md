# The Mission:
To make a working Unity Game where the model of the Perseverence Rover can be driven around in a handheld device on a AR plane.

# The Challenge:
I do not have a Macbook. Or an iPhone for the moment. So developing for iOS is difficult. In the middle of the development cycle, my only android device broke down and died (to be fair to it, it was about 4 years old but shhh). So, longer development time and painstaking simulators. For code, it was pretty straight forward.

# The How To Play
In the project, ARFoundation 5.0+ is used so ARSimulation is available. Controls are:
- Hold Right mouse button and move mouse for panning
- W/A/S/D haxxx for moving the camera forward/left/back/right
- Q/E for down/up movement

For Touch Control Simulation, Once happy with the plane detection, Open Input Debugger from *window>Analysis>InputDebugger*
![image](https://github.com/NirabhraDas013/MarsRoverTest/assets/54432376/e59aadab-791d-46fc-8995-30d0587f83d5)

(Or keep it docked beside the inspector like I did in mine)

![image](https://github.com/NirabhraDas013/MarsRoverTest/assets/54432376/ca47e3b1-ec83-4809-aefc-4bff5c4e31ec)

The reason for that is the AR Simulator and the Touch Simulator apparently hate each other and one will not come out while the other is playing. And when I turn on the Touch simulator from the options in the Input Debugger

![image](https://github.com/NirabhraDas013/MarsRoverTest/assets/54432376/81365a03-1600-48c1-ad2b-7c5a5c7e399c)

The AR Simulator starts sulking and stops working

So, The Touch Simulator has to be turned off again after the Rover Model is spawned so we can test the AR in simulation.

For the Rover Arm, I used a IK asset I had bought a while ago called HybridIK. It's not perfect but for rapid idea design purposes, it's quite good. In any production scenario though, a custom solution based on the existing assets and/or systems would be preferable. 

Same with the Wheel Colliders. I have not done much with the wheel colliders as Unity's wheel collider system (at least according to majority of users) is too complex for a good arcade wheel while not complex enough for a realistic wheel. (Go figure. Well Done Unity, Well Done.)


And Finally Here's a little almost but not quite 2 minute long video of the project. Although I hav no idea why it is 200MB!!


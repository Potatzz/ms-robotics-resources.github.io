# Making Your First TeleOp Program
This page will walk you through making your first TeleOp program in Andriod Studio. Make sure you have Road-Runner and Andriod studio installed, if you don't you can go [here](https://potatzz.github.io/ms-robotics-resources.github.io/code_setup.html) to install them.

# Some Terminology and Structure First
Before we begin, let's go over some basic terminology, I highly suggest you also look at the (code library) as well.
The robot uses two pieces of hardware to interpret and run the code:
- **The Driver Station** which allows the driver to run and get values from your code.
- And, **The Control Hub** which actually outputs the code and runs the motors


When writing your code, there are a few methods that are required for the robot to run. 
The first required method is `init()`, which runs **once** when you pres "Init" on the Driver Station.
The second required method is `loop()`, which runs 50x a second.
There are 3 other methods that are optional, `init_loop()`,`start()` and `stop()`.
`init_loop()` runs 50x a second after you press "Init" and before you press start, which gets added as another button on the Driver Station.
`start()` runs once after you press start, and `stop()` runs once after you press stop.

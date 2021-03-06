# Little Flockers
My favorite project from CS 440 - Intro to Artificial Intelligence (Fall 2015)

It's an exercise in AI programming with Java. Use XML files to create a virtual environment filled with agents and obstacles. Program the behaviors of the agents in Java. Specifically Java 7, but it probably supports older versions.

![A screenshot of the simulation in action](https://raw.githubusercontent.com/brandon8000/Little-Flockers/master/Flockers.JPG "Look at those flockers go!")

How To Use
----------
1. Fork this git repository or clone it as is
  - `git clone <repository URL>`
2. Go into the repository folder
  - `cd Little-Flockers`
3. Compile the java source code files into the 'bin' folder
  - `javac -d bin *.java`
4. Run any of the simulations located in the xml folder
  - `java -cp bin Simulation ./xml/<any xml file>`

How To Modify
-------------
The source file names should be a big hint but the functions to control the bird behaviors are located in Flocker.java starting at line 492

Follow the templates of the existing XML files to create your own that will instantiate new environments.

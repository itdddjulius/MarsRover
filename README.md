# Julius Olatokunbo - Mars Rover React - v1.0

		// === MODULE  - index.html - (Julius Olatokunbo - Mars Rover React - v1.0)
		// ===
		// === AUTHOR  - Julius Olatokunbo
		// ===
		// === WRITTEN - SUN - 10-JAN-2021
		// ===
		// === REASON - Julius Olatokunbo - Mars Rover JS v1.0
		// ===        - Index.Html is a MarsRover algorithm in JS
		// ===        - Think of this challenge as an opportunity to show us what “good” looks like to you; and a fun way to
		// ===        - showcase your skills.
		// ===        - 
		// ===        - Here are some tips and guidelines:
		// ===        -  Language and tools: React (required on the front end) + something on the backend (e.g.
		// ===        - Node.js. Python etc)
		// ===        -  Focus is on the front-end design and implementation, back-end is only necessary to make
		// ===        - front-end work.
		// ===        -  Provide enough instructions for setting up and running the application.
		// ===        -  Use additional frameworks as necessary, and to present your skills.
		// ===        -  GUI should use any browser related technologies.
		// ===        -  KISS - Keep it Simple Stupid.
		// ===        -  Put your code on GitHub and give us the URL.
		// ===        -  Commit history is important; we are interested to see how you approach the challenge and
		// ===        - how you verify the validity of your solution.
		// ===        -  Provide documentation within the repository how to run the application. We need to be
		// ===        - able to run it using this documentation.
		// ===        - Problem: Martian Robots
		// ===        - 
		// ===        - The Problem
		// ===        - The surface of Mars can be modelled by a rectangular grid around which robots are able to move
		// ===        - according to instructions provided from Earth. You are to write a program that determines each
		// ===        - sequence of robot positions and reports the final position of the robot.
		// ===        - A robot position consists of a grid coordinate (a pair of integers: x-coordinate followed by y-
		// ===        - coordinate) and an orientation (N, S, E, W for north, south, east, and west). A robot instruction is a
		// ===        - string of the letters “L”, “R”, and “F” which represent, respectively, the instructions:
		// ===        -  Left: the robot turns left 90 degrees and remains on the current grid point.
		// ===        -  Right: the robot turns right 90 degrees and remains on the current grid point.
		// ===        -  Forward: the robot moves forward one grid point in the direction of the current orientation
		// ===        - and maintains the same orientation.
		// ===        - The direction North corresponds to the direction from grid point (x, y) to grid point (x, y+1). There is
		// ===        - also a possibility that additional command types may be required in the future and provision should
		// ===        - be made for this.
		// ===        - Since the grid is rectangular and bounded (...yes Mars is a strange planet), a robot that moves “off”
		// ===        - an edge of the grid is lost forever. However, lost robots leave a robot “scent” that prohibits future
		// ===        - robots from dropping off the world at the same grid point. The scent is left at the last grid position
		// ===        - the robot occupied before disappearing over the edge. An instruction to move “off” the world from
		// ===        - a grid point from which a robot has been previously lost is simply ignored by the current robot.
		// ===        - 
		// ===        - The Input
		// ===        - The first line of input is the upper-right coordinates of the rectangular world, the lower-left
		// ===        - coordinates are assumed to be 0, 0.
		// ===        - The remaining input consists of a sequence of robot positions and instructions (two lines per robot).
		// ===        - A position consists of two integers specifying the initial coordinates of the robot and an orientation
		// ===        - (N, S, E, W), all separated by whitespace on one line. A robot instruction is a string of the letters “L”,
		// ===        - “R”, and “F” on one line.
		// ===        - Each robot is processed sequentially, i.e., finishes executing the robot instructions before the next
		// ===        - robot begins execution.
		// ===        - The maximum value for any coordinate is 50.
		// ===        - All instruction strings will be less than 100 characters in length.
		// ===        - 
		// ===        - The Output
		// ===        - For each robot position/instruction in the input, the output should indicate the final grid position
		// ===        - and orientation of the robot. If a robot falls off the edge of the grid the word “LOST” should be
		// ===        - printed after the position and orientation.
		// ===        - Sample Input (somehow through the GUI)
		// ===        - 5 3
		// ===        - 1 1 E
		// ===        - RFRFRFRF
		// ===        - 3 2 N
		// ===        - FRRFLLFFRRFLL
		// ===        - 0 3 W
		// ===        - LLFFFLFLFL
		// ===        - 
		// ===        - Sample Output
		// ===        - 1 1 E
		// ===        - 3 3 N LOST
		// ===        - 2 3 S
		// ===        - 
		// ===        - 
		// ===        - Run / Build
		// ===        -       To START Development, run `npm start` or `yarn start`.
		// ===        -       To BUILD Production bundle, use `npm run build` or `yarn build`.
		// ===        - 
		// ===        - 
		// === HISTORY- ===========================================================================================================================
		// === J.O. 10-JAN-2021 - v1.0 - Initial flash param loading to establish communication with server, trace output to console
		// === J.O. 11-JAN-2021 - v1.0 - Alert panel, Logo and Alert Button modification with all text accessed from Locale file 
		// === J.O. 11-JAN-2021 - v1.0 - Param interpretation 
    	// === J.O. 11-JAN-2021 - v1.0 - Configure LOST Spin functionality
	  	// === J.O. ===============================================================================================================================
![alt text](http://url/to/img.png)
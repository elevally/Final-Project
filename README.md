# Final-Project
The 12 steps toward rock solid scientific python code are
1. Use version control - Seriously, keep track of what you are doing, and have several versions to revert to if necessary
2. Put your code in the cload - Makes sense.
3. Add a Readme and a Liscense - know what you are doing, why, and make sure anyone you allow to modify your code also knows these things
4. Write docstrings - always know what your functions are doing
5. Write tests - best way to avoid debugging
6. Keep track of issues - keeps you from losing your mind
7. Automate the tests - you can't forget to run it if it does it on its own.
8. Automate the build.
9. Use continuous integration
10. Monitor test coverage
11. Write narrative documentation
12. Catch errors as you type them

What I hope to use my physics degree for is some form of engineering.  I want it to get a masters in mechanical, architectural, or areospace engineering.  I am very interested in classical systems that involve projectile motion, or statics.  That is why I am thinking of doing problem 2.3 from Giordano's text.  It expands upon what I did for my project 1, but also allows me to use some of the ideas and code I created earlier.  I will be using Euler's method in order to solve parts of this problem.  Another idea that I might be interested in is the patriot missle.  It is a ballistic system that intercepts incoming missles so that they cannot make contact with troops on the ground.  In order to do this problem, I would probably need the code from my cannon shell project, and also be able to determine exactly where a second projectile would come in contact with the initial one.

Project
1.  The general area of physics that this project relates to is projectile motion.
2.  The relevant controlling equations are those of a projectile with air resistance, using an Euler method. They are: $$ x(t+h) = x(t) + hf(x,t) $$ 
$$ x_{i+1} = x_{i} + v_{x,i}\Delta t$$  
$$ v_{x,i+1} =  v_{x,i}$$
$$ y_{i+1} = t_{i} + v_{y,i}\Delta t$$  
$$ v_{y,i+1} =  v_{y,i} - g\Delta t$$ 
$$ x_{i+1} = x_{i} + v_{x,i}\Delta t$$
$$ v_{x,i+1} =  v_{x,i} - \frac{B_{2}v v_{x,i}}{m}\Delta t$$
$$ y_{i+1} = t_{i} + v_{y,i}\Delta t$$
$$v _{y,i+1} =  v_{y,i} - g\Delta t - \frac{B_{2}v v_{y,i}}{m}\Delta t$$
3.  The specific scenario that this code will simulate is the interception of one projectile by another. 
4.  I plan on using the Euler method and the bisection method in order to model this problem.
5.  The boundaries of this scenario will be that the minimum initial velocity of each projectile will be 3,000 m/s and the maximum of each will be 3,500 m/s.  The firing angles will be a minimum of 20 degrees and a maximum of 75 degrees.
6. A missile will be coming at us with a random velocity at a random angle, and the program will calculate and output the correct angle and speed that out intercepting missile will need to fire at in order to intercept the incoming missile at a maximum possible height.  The output of the program should be an angle and a velocity, and I hope to write another function to show a graph of the two projectiles.  To verify that my results are correct or reasonable, I can do the calculations by hand and then compare them to the output of my program.
7.  Step 1: complete code for a random incoming projectile  Completed by end of class Friday
    Step 2: complete code for a projectile fired in the opposite direction  Completed by end of class Monday
    Step 3: complete code to determine where they will intercept  Completed by end of class Thursday
    Step 4: complete code to determine maximum height of intersection, and find the angle and velocity to reach it  Completed by end of class next Friday
    Step 5: Make pretty graphs and write all required intros, descriptions  Completed by end of semester.

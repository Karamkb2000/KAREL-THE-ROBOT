# KAREL-THE-ROBOT
Chapter 1
Introducing Karel the Robot
In the 1970s, a Stanford graduate student named Rich Pattis decided that it would be
easier to teach the fundamentals of programming if students could somehow learn the
basic ideas in a simple environment free from the complexities that characterize most
programming languages. Drawing inspiration from the success of Seymour Papert’s
LOGO project at MIT, Rich designed an introductory programming environment in
which students teach a robot to solve simple problems. That robot was named Karel,
after the Czech playwright Karel Capek, whose 1923 play R.U.R. (Rossum’s Universal
Robots) gave the word robot to the English language.
Karel the Robot was quite a success. Karel was used in introductory computer science
courses all across the country, to the point that Rich’s textbook sold well over 100,000
copies. Many generations of CS106A students learned how programming works by
putting Karel through its paces. But nothing lasts forever. In the middle of the 1990s, the
simulator we had been using for Karel the Robot stopped working. We were, however,
soon able to get a version of Karel up and running in the Thetis interpreter we were using
at the time. But then, a year ago, CS106A switched to Java, and Karel again vanished
from the scene. For the last three quarters, the hole in the curriculum left by Karel’s
departure has been competently filled by Nick Parlante’s Binky world, but it seems about
time to bring Karel back. The new implementation of Karel is designed to be compatible
with both Java and the Eclipse programming environment, which means that you’ll get to
practice using the Eclipse editor and debugger from the very beginning of the course.


What is Karel?
Karel is a very simple robot living in a very simple world. By giving Karel a set of
commands, you can direct it to perform certain tasks within its world. The process of
specifying those commands is called programming. Initially, Karel understands only a
very small number of predefined commands, but an important part of the programming
process is teaching Karel new commands that extend its capabilities.
When you program Karel to perform a task, you must write out the necessary
commands in a very precise way so that the robot can correctly interpret what you have
told it to do. In particular, the programs you write must obey a set of syntactic rules that
define what commands and language forms are legal. Taken together, the predefined
commands and syntactic rules define the Karel programming language. The Karel
programming language is designed to be as similar as possible to Java so as to ease the
transition to the language you will be using all quarter. Karel programs have much the
same structure and involve the same fundamental elements as Java programs do. The
critical difference is that Karel’s programming language is extremely small, in the sense
that it has very few commands and rules. It is easy, for example, to teach the entire Karel
language in just a couple of hours, which is precisely what we do in CS106A. At the end
of that time, you will know everything that Karel can do and how to specify those actions
in a program. The details are easy to master. Even so, you will discover that solving a
problem can be extremely challenging. Problem solving is the essence of programming;
the rules are just a minor concern along the way.
In sophisticated languages like Java, there are so many details that learning these
details often becomes the focus of the course. When that happens, the much more critical
issues of problem solving tend to get lost in the shuffle. By starting with Karel, you can
concentrate on solving problems from the very beginning. And because Karel encourages
imagination and creativity, you can have quite a lot of fun along the way.




What Karel should do in My code:
Divide a given map into 4 + 4 as shown in the diagram – Do all the analysis to handle the special cases. i.e. maps that can't be divided into the required shape because it's too small. 

Notes:
  - The inner chambers should be the biggest possible equals squares.
  -  The outer chambers should be equal in size, and they should be L-shaped (they shouldn't be rectangles or squares). 

  - You are allowed to use double lines of beepers if you need to, however, you need to observe that beepers use should be optimized.
Notes:
-	Assume having enough number of beepers (say 1000) in Karel’s bag. You can use the API to setup an initial value of the beepers.
-	You can’t use the classes API to solve the assignment, and you should be using only the functions given in Karel reference card. Karel is a black box that came out of the factory with certain capabilities according to it’s reference card. The only exception to that is initializing Karel’s bag with beepers. 



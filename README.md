# Disruptor-Daj

This is my repository for testing out the Disruptor library from LMAX.  It is written against Disruptor-2.7. You can get the code here: http://code.google.com/p/disruptor/downloads/list

# Demo Code

Not all the documentation at http://code.google.com/p/disruptor/ is up to date, so the best way to get the latest is read the source code and tests and javadoc.

I have created short demonstrations of how to do various things with the API - these are supplements to reading the Disruptor unit tests.  I find some of the unit tests with various Mock objects adding to the noise in trying to follow how to do this.  

My demos are not unit tests - they are simple demos with println statements and you can analyze the println output with the code to see how to do something.

# Build and run

There is an Ant build file.  The only requirement is that you copy the disruptor-2.7.jar to the lib directory created by the Ant build file (or make a symlink to it).  There are no other dependencies, other than Java 6.

# Future 

More will be coming later, including more complicated applications with it.

-Michael Peterson
November 2011

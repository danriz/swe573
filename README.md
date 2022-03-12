# swe573 Ömer Faruk Çevik
project progress of swe 573 course in the year 2022 spring.
## installing django
I tried to install django. It seems simple, but unexpected errors suprised me. I have a new mac computer with m1 processor. I thought while I was purchasing the m1 computer that all the compatible software will be available in a few months. Unfortunately, it is not.
When I run the command to install posgresql 
sudo apt install python3-dev libpq-dev
chain of errors poped-up.

Last login: Sat Mar 12 15:55:48 on ttys000
ofc2@Omers-MacBook-Pro ~ % sudo apt install python3-dev libpq-dev

Password:
The operation couldn’t be completed. Unable to locate a Java Runtime that supports apt.
Please visit http://www.java.com for information on installing Java.

In my old mac, my computer had buildin, up and working java. It suprised me that macosx does not build-in java.
I search internet to find a java version compatible with m1 processor. 
I downloaded java and tried to run it. Bu home variable is not configured.

echo $JAVA_HOME
command prints null.
I searched a source to confiure $JAVA_HOME variable. 

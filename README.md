# swe573 Ömer Faruk Çevik
project progress of swe 573 course in the year 2022 spring.
## installing django 12.02.2022
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
the web page below provides relative information.
https://wolfpaulus.com/java-on-macos-big-sur/

## step2
I installed postgresql for macosx manually. I managed to run my website in my local host by making google searches whenever I faced with an error.
I used my username in operating system (ofc2) in postgresql. I put the same username to configuration file. 
my postgresql is running in local host and django is also running.
I still can not start java in my local computer.
<img width="1432" alt="s4" src="https://user-images.githubusercontent.com/5708061/158053383-4f91fa3d-f9a5-4eec-adea-9f6d65413bd1.png">

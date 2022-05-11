# swe573 Ömer Faruk Çevik
project progress of swe 573 course in the year 2022 spring.
## step 1- installing django 12.02.2022
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

## step2 - start local server
I installed postgresql for macosx manually. I managed to run my website in my local host by making google searches whenever I faced with an error.
I used my username in operating system (ofc2) in postgresql. I put the same username to configuration file. 
my postgresql is running in local host and django is also running.
I still can not start java in my local computer.
<img width="1432" alt="s4" src="https://user-images.githubusercontent.com/5708061/158053383-4f91fa3d-f9a5-4eec-adea-9f6d65413bd1.png">

<img width="870" alt="s6" src="https://user-images.githubusercontent.com/5708061/158053779-78bb7731-2156-40b2-b340-e59899a32956.png">
<img width="1339" alt="s3" src="https://user-images.githubusercontent.com/5708061/158053785-a04c5b00-b606-4243-b530-6866f035f8ad.png">
<img width="1003" alt="s2" src="https://user-images.githubusercontent.com/5708061/158053798-614d838c-f164-455b-8f75-68582794473d.png">
<img width="704" alt="s1" src="https://user-images.githubusercontent.com/5708061/158053839-c6822767-8858-4c1e-ac09-a4747bfff45a.png">

## step3 - deployment
 
 I failed to deploy. I think it is because pythoneveryhwhere requires paid membership to postgresql. I have to switch mysql.
 <img width="1220" alt="Screen Shot 2022-03-13 at 12 46 55" src="https://user-images.githubusercontent.com/5708061/158054010-5a364267-1cf7-4bc4-b899-0398f84aa579.png">

## restart server one day later

ofc2@Omers-MacBook-Pro ~ % psql postgres
ofc2@Omers-MacBook-Pro ~ % source myvenv/bin/activate
(myvenv) ofc2@Omers-MacBook-Pro ~ % cd djangogirls
(myvenv) ofc2@Omers-MacBook-Pro djangogirls % source myvenv/bin/activate
(myvenv) ofc2@Omers-MacBook-Pro djangogirls % django-admin startproject mysite .

## application is running on my local

The application is performing well on my local computer with a postgresql. Its video is here:
https://youtu.be/lY7y_AMTW1U

I can not transfer to the pythonanywhere server.
I followed the directions there to make an up and running site.
https://blog.pythonanywhere.com/155/
In other words I created the web site via wizard.
I will manually configure settings to convert it to djangogirls tutorial.

## the learning portal design
As a system analyst professional for years, I have faced software failures dozens of times. Those failures happens because the related requirements are not gathered properly at the beginning. So, firstly I tried to collect as much as information at the beginning. I have talked with a teacher friend, search for internet and so on. I want to emphasis that I am not an educator and I have no experience with education. Also I have no experience with human psychology. Thus professional educators and psychologists should ne involved in a serious project.
### three impartant factors in learning
As far as I understant from my searches the intelligence level of an individual, the character of the person and familarity with the topics are three important factor for determining a candidate student's level.  
<p>the first one is the intelligent quality of an individual for quantitative courses. People with higher IQ probably can learn faster in quantitative courses. Thus, the content for a quantitative course for a person with low IQ can be large while for people with high IQ they might be short lectures. In this way, some people do not get bored quickly while some people do not dropout the course because they do not understand.  
 ### quizlet question preperation
 I found the website quizlet.com as a good example for question preperation.
 


#### Big-Rich-Man
this subject is depend on  Random Big Rich Man(瑞德大富翁) is monopoly-like game using random map to play. It's local game with 4 AI/Human player.

including is https://git-lab-com/movep/Random-Big-Rich-Man


## Files 

# Random-Big-Rich-Man-master.zip is sourcecode file 

# random-big-rich-man-1.0.0-SNAPSHOT is target file  
"
mvn exec:java
 or
java -jar random-big-rich-man-*.jar   " 

to run it 


========================================



# Assets
Image or Sound from these projects or the Internet:

gtkmonop-0.3.0
kapitalist-0.4
monopolie-0.9.7


# Install preconditions

Java 1.8.0 or newer
Maven 2.2.1 or newer


# Game Features

Random map


# Game Rules

Monopoly-like game rule
Land Tax: each land $400
House Tax: each house $200, hotel is $800
Question Mark event:
a. give player money
b. pay money
c. forward steps
d. go to start point or parking lot
e. stop once
f. ...
Go to hospital will pay $1000
Toll is 20% of land value
Toll is double each house
Toll is 1600% if land have hotel
Player can build hotel if 3 houses on the land
If player buy all same color land, toll is double
Toll free if land owner is in jail
Player exceed start point will give $2000, but $0 if on the start point
Go to jail stop 3 turns


# How to build and run
to build:
mvn package
to run:
mvn exec:java
 or
java -jar target/random-big-rich-man-*.jar



========================================




01/26/2022
increment function with curl calls to get count of interactions into the cloud database
  lambda serverless with database integration

Face detection to see where people are looking
  OpenCV in python, face detection
  https://towardsdatascience.com/face-detection-in-2-minutes-using-opencv-python-90f89d7c0f81
  Increment on the faces seen - timing with delay to track again
  Masks could be a problem
  Distance tracker, if moving away then go off

Optimization of scariness - or holding back
  Run away is a success

Motion tracking puzzle - ML unlocking for larger candy
  Can change to different patterns to make it variable
  Accelerameters for tracking motion
  
Path of people movement
  Distance tracking or cameras

Color changing for reactions

Puzzles to solve

Dispensing function for candy
  Single candy in the bin
  When closed another drops in
  
Walk the plank and walk back you get a candy

Talking Parrots
  Triggered if someone gets close enough
  Asks question
  Text response and learning model
  Chatbot with responses
Treasure Chests
Walk the Plank
Sailing - Sails
Salt Water
Fight Kraken
  When you get close get grabbed by sea monster
Pirate Songs

## Added 2/9
Would be good to have a central hub with control and status of the various connected items
Visual layout with items color coded by active, inactive or error
Able to quickly switch between scenarios (toddler, child, teenager, adult)
Individual items could be specifically turned on and off
Individual items could be fired manually if needed
Websocket implementation where subscribers get messages to turn active or inactive, fire or not and send messages with their status when available

## Added 2/23
Network Options
  Bluetooth
  Wifi - Local (Yard-fi)
  Wifi - Internet
  
Yard-fi
  RPi main hub
  Talking to each Wifi enabled Arduino Device
  Need to set up a few Wifi enabled devices and get them networked to talk to one another
  Orchestration from the main hub, On/Off high/med/low , general setting and error codes
  
Homework - Do we want websockets or HTTP (TCP) or Websocket (UTP) protocol
  NOTE: Will have many devices up to 10 so need to plan network for that
  Goal: Setup basic connection that works "Hello World" for our network solution
    Connection between devices on the local network
    One device turns on light in the other and writes to the database through endpoint
    

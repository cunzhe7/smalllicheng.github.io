---
layout: page
title: Projects
---

[My github](https://github.com/smalllicheng)

## NeRF
I gave another presentation on [Intelligent Visual Computing: A Neural Network Approach](https://people.cs.umass.edu/~kalo/courses/visual_computing/index.html) course about NeRF, the [slides](/images/NeRF_presentation_chengzhe.pdf) is here. It was a great course, and I learned a lot about 3D Computer Graphics and Vision. In both tranditional approaches and machine learning approaches! It was one of the best course I've ever taken!

## [CompressedNeurons](https://github.com/smalllicheng/superneurons-release)
* Worked on existing research project SuperNeurons, a framework designed to improve GPU memory efficiency. Researched, reproduced, and tested the existing framework. Implementing new allocating method to further improve and efficiency to adapt larger batcher size and deeper network.

* I also gave a presentation about Autophase(Ameer et al.), a machine learning solution for compiler phase ordering problem, on the CS692(Sys for ML, ML for Sys) Seminar. We also did a lot of paper reading and reviewing in this course. A very interesting and educational course! Thank you Prof Hui.
[Autophase Presentation](/images/AUTOPHASE.pdf)


## [Face-mask detector](https://github.com/smalllicheng/face-mask)
Detect human faces and masks in crowds in real time. Aiming to deploy on poor performance devices, investigated plenty of face detection models like Faster R-CNN, Blazeface, MobileNet, etc.. and made optimization. End to end application used OpenCV2 and TensorFlow.
![mask](/images/Mask.jpg)


## [CookingPapa](https://github.com/smalllicheng/CookingPapa)
* Game developed used Unity. The idea is the player needs to fight with the monsterized animal or vegetable to get the food material. Some other material will be hidden on the map or looted by some other ways. After gathering all materials, there will be a real-life simulated cooking stage for the player to play and learn
* Chose the assets used, deigned the game logic, and implemented the gameplay. Set up the scenes, UI, etc..
* Added videos, BGMs, and sound effects to make the game more enjoyable
* Added clear instructions, particle systems, and physical to make the game harder but more interesting
* The playable game and demo video are available on my Github


## Pygmy Market
* Pygmy is a simulated online bookstore using micro services. We built frontend server, order server, and catalog server as three separate RESTful micro services by Flask, and a simple command-line user interface to interact with it. Worked in a team with two
* Used Sqlite3 as the lightweight database and storing information on catalog server. The frontend server supports three operations, search(category), lookup(item), and buy(item) goes to two backend servers.
* Besides the basic functionalities, we implemented support for replication and synchronization on backend servers, cache on frontend servers, load balancing, and crash fault tolerance and recovery. We also used Docker to containerize our microservers so it’s easier to deploy


## Bazzar
P2P networks built in Python, used pyro4 as RPC library, nodes were able to raise lookup call to buy items using Gossip protocol. The message would be passed by RPC function. The structure of the network was configurable. Multiple transactions can be processed at the same time. Worked in a team with two 
![](/images/Bazaar.png)



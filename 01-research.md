---
layout: page
title: Research
permalink: research.html
---

- [Finding an Interaction Partner in a Crowd (User Study)](#finding-an-interaction-partner-in-a-crowd-user-study) 
- [Robust Sensor Fusion for Finding HRI Partners in a Crowd](#robust-sensor-fusion-for-finding-hri-partners-in-a-crowd)
- [Selecting and Commanding a Subset of a Group of Robots](#selecting-and-commanding-a-subset-of-a-group-of-robots)
- [A Robust Integrated System for Selecting and Commanding Multiple Mobile Robots](#a-robust-integrated-system-for-selecting-and-commanding-multiple-mobile-robots)

## Finding an Interaction Partner in a Crowd (User Study)

### Summery

Robots navigating crowded, uncontrolled environments may have to choose the most promising interaction partner among a group of people. This requires a system for measuring interest, identifying attention-seeking signals from an interested party, and approaching them. One solution could be manually controlling the robot and driving it toward someone for close- range one-on-one interaction, however, the user would have to carry a controller and be trained to use it. We propose an alternative autonomous interaction system, which allows any human to start an interaction with a ground mobile robot without instrumentation. For robustness, the system integrates three multimodal human percepts and has the robot approach the point with the highest probability of an interested human, communicating its current state and intention with audio and light feedback. This paper presents a study conducted with our functional and publicly available system and a pool of untrained users to evaluate its performance both objectively and as perceived by participants. We also report on the observation from the users’ natural behavior when asked to “make the robot come to you”. The study compares our system to 1) a teleoperated alternative and 2) an ideal autonomous robot responsive to all human attention-seeking signals. Both qualitative and quantitative results show our system is preferred by 82% of the users, and performs as well or better than its competitor in all measured areas.

### Demo

<div class="grid grid-pad">

    <div class="col-1-1">
       <div class="content">
           <iframe width="560" height="315" src="https://www.youtube.com/embed/3cj7v6cq3Vc" frameborder="0" allowfullscreen></iframe>
       </div>
    </div>

</div>   

<hr>

## Robust Sensor Fusion for Finding HRI Partners in a Crowd

### Summery

We present a simple probabilistic framework for multimodal sensor fusion that allows a mobile robot to reliably locate and approach the most promising interaction partner among a group of people, in an uncontrolled environment. Our demonstration integrates three complementary sensor modalities, each of which detects features of nearby people. The output is an occupancy grid approximation of a probability density function over the locations of people that are actively seeking interaction with the robot. We show empirically that simply driving towards the peak of this distribution is sufficient to allow the robot to correctly engage an inexperienced user in a crowd of bystanders.

### Demo

<div class="grid grid-pad">

    <div class="col-1-1">
       <div class="content">
           <iframe width="560" height="315" src="https://www.youtube.com/embed/PLB6OQWqaUs" frameborder="0" allowfullscreen></iframe>
       </div>
    </div>

</div>  

<hr>


## Selecting and commanding a subset of a group of robots

### Summery

We present a multimodal system for creating, modifying and commanding groups of robots from a population. Extending our previous work on selecting an individual robot from a population by face engagement, we show that we can dynamically create groups of a desired number of robots by speaking the number we desire, e.g. “You three”, and looking at the robots we intend to form the group. We evaluate two different methods of detecting which robots are intended by the user, and show that an iterated election performs well in our setting. We also show that teams can be modified by adding and removing individual robots: “And you. Not you”. The success of the system is examined for different spatial configurations of robots with respect to each other and the user to find the proper workspace of selection methods.

### Demo

<div class="grid grid-pad">

    <div class="col-1-1">
       <div class="content">
           <iframe width="560" height="315" src="https://www.youtube.com/embed/I8sJud-OApw" frameborder="0" allowfullscreen></iframe>
       </div>
    </div>
</div> 

<div class="grid grid-pad">

    <div class="col-1-1">
       <div class="content">
           <iframe width="560" height="315" src="https://www.youtube.com/embed/heiYPVGFnEM" frameborder="0" allowfullscreen></iframe>
       </div>
    </div>
</div> 

<hr>

## A Robust integrated system for selecting and commanding multiple mobile robots

### Summery

We describe a system whereby multiple humans and mobile robots interact robustly using a combination of sensing and signalling modalities. Extending our previous work on selecting an individual robot from a population by face-engagement, we show that reaching toward a robot - a specialization of pointing - can be used to designate a particular robot for subsequent one-on-one interaction. To achieve robust operation despite frequent sensing problems, the robots use three phases of human detection and tracking, and emit audio cues to solicit interaction and guide the behaviour of the human. A series of real-world trials demonstrates the practicality of our approach.

### Demo

<div class="grid grid-pad">

    <div class="col-1-1">
       <div class="content">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/WLwb7gJOl8w" frameborder="0" allowfullscreen></iframe>
       </div>
</div>

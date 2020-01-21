## Introduction

You are going to learn how to create a game in which a helicopter scores points by watering flowers in the city.

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/110929020/?autostart=false" frameborder="0"></iframe>
  <img src="images/flowers-final.png">
</div>

### Additional information for club leaders

If you need to print this project, please use the [Printer friendly version](https://projects.raspberrypi.org/en/projects/green-your-city/print).


--- collapse ---
---
title: Club leader notes
---


## Introduction:
In this project, children will create a game in which a helicopter scores points by watering flowers in a city.

## Resources
For this project, Scratch 2 should be used. Scratch 2 can either be used online at [jumpto.cc/scratch-on](http://jumpto.cc/scratch-on) or can be downloaded from [jumpto.cc/scratch-off](http://jumpto.cc/scratch-off) and used offline.

The 'Project Materials' link for this project contains the following resources:

##### Club leader Resources

You can find a completed version of this project <a href="http://scratch.mit.edu/projects/110929020/#editor">online</a>, or it can be downloaded by clicking the 'Project Materials' link for this project, which contains:

+ GreenYourCity.sb2

##### Project Resources

For this project, club members can make use of a Scratch project containing the required resources. This project is available at [jumpto.cc/city-resources](http://jumpto.cc/city-resources), or it can be downloaded by clicking the 'Project Materials' link for this project, which contains:

+ GreenYourCityResources.sb2

Make sure that each child has access to a copy of these resources.

## Learning Objectives
+ This project consolidates learning of previous programming skills learnt.

This project covers elements from the following strands of the [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Combine programming constructs to solve a problem.](https://www.raspberrypi.org/curriculum/programming/builder)

## Challenges
+ "Animate your helicopter" - use a `next costume`{:class="blocklooks"} block to animate the helicopter;
+ "Too much water" - using `wait`{:class="blockcontrol"} blocks to slow down the rate that water is dropped;
+ "Keeping score" - adding a `score`{:class="blockdata"} variable to the game, that is increased each time a flower is watered;
+ "Floating flowers" - fixing the flowers to only move if they aren't high enough.

## Frequently Asked Questions
+ The simplest way to move the helicopter across the stage is to use the following code:

```scratch
repeat until < touching [edge v] ?>
    move (3) steps
end
```

This means that the helicopter will not move if it's starting position is on an edge of the stage. To fix this problem, just ensure that the helicopter's starting position (in the `goto`{:class="blockmotion"} and `set`{:class="blockmotion"} blocks) is away from the stage edges.

--- /collapse ---

--- collapse ---
---
title: Project materials
---

## Project resources
* [Online Scratch 2 project containing external resources](http://jumpto.cc/city-resources)
* [Downloadable Scratch 2 project containing external resources](resources/GreenYourCityResources.sb2)

## Club leader resources
* [Online completed Scratch 2 project](http://scratch.mit.edu/projects/110929020/#editor)
* [Downloadable completed Scratch 2 project](resources/GreenYourCity.sb2)

--- /collapse ---
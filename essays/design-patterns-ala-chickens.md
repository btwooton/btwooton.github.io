---
layout: essay
type: essay
title: [Design Patterns: As Explained by Chickens]
# All dates must be YYYY-MM-DD format!
date: 2018-05-01
labels:
  - Design Patterns
  - Software Engineering
---

## A Convenient Heuristic

<img class="ui small right floated rounded image" src="../images/ninja_chicken.png">
Design patterns are essentially prepackaged, general purpose solutions that can be applied to solve common problems that frequently crop up in the design of complex software systems. Design patterns have been claimed to enable rookie coders to harness the powers of the infamous hacker ninja! However, the concept of design patterns is far from a trivial one, which is why I have decided to leave it up to the chickens to elaborate on the intricacies of this subject. The biological life history of any jungle fowl can be summarized into three broad topics: creation, structure and behavior.

## Creation
<img class="ui small left floated rounded image" src="../images/funny_chickens.jpeg">
<img class="ui small right floated rounded image" src="../images/chicken_or_egg.jpg">
<img class="ui small left floated rounded image" src="../images/chicken_factory.jpg">
The start of any great story begins with creation, and chickens are surely no exception to this. Sometimes, we want to be able to go off and manufacture a diverse array of chickens, without getting bogged down by the details of how to actually create each individual hen or rooster. When placed in the precarious position of needing to produce a potpourri of poultry-perfection, one should surely leave it up to a factory to yield the desired products. The primary benefit of delegating the creation of chickens to a factory, is that the factory is essentially capable of creating any quantity, and any type of chicken you could imagine, such as the majestic “honor your ancestors chicken.”
<figure>
<img class="ui large centered rounded image" src="../images/chicken_dinosaur.jpg">
  <figcaption style="text-align: center"><em>In case you were wondering, chicken actually inherits from dinosaur</em></figcaption>
</figure>

<img class="ui small right floated rounded image" src="../images/singleton_chicken.png">
On the other hand, we may instead find ourselves requiring a solitary exemplar of avian majesty, the ownership of which lies not in the hands of any single chicken connoisseur, but whose glory is instead made available to the entire globe upon which it stands, to be gazed upon in awe and wonder. In this case, look no further than the magnificent “singleton chicken!” After all, what good is it to have a multitude of sub-par chickens, when we can have a single chicken that suits our needs better than all of the rest?

## Structure

While chickens certainly exhibit a highly predictable bodily structure, with feathers, wings, a beak, and talons, there is much that we can do to elaborate on this seemingly mundane phenotype. Are you a bored bird shepherd, looking to add variety to your flock? Instead of investing precious time and scarce resources in a new group of Galliforms, enlist the aid of the “decorator chicken!” The decorator chicken has the just the right touch of creativity to help each of your chickens learn new behavior, find a new purpose, and gain a new lease on life. 

## Behavior

Many people falsely believe that chicken behavior is a dry, boring subject. Those people are completely unaware of the existence of the elusive and daring “observer chicken!” When danger is lurking just outside of the hen house, the observer chicken is able to notify his fellow chickens who depend upon him to alert them of potential risks, so that they may respond accordingly. The observer chicken is truly  an exemplar of the complex behavior that these seemingly mundane organisms can exhibit.

## An Author’s Forays into the Fowlery

During my time as a lead developer on the Shaka Scheme project, I was presented with many opportunities to leverage the aforementioned design patterns to aid me in tending to my flock. At one point, I discovered that I required a means by which to ensure that the resources devoted to the creation of each chicken would eventually be recycled, without needing to manage the gruesome task myself. In accomplishing this, I leveraged a special instance of the factory pattern to ensure that any expired or unneeded chickens would be dealt with accordingly.  Enter the “garbage collector chicken!” Just kidding, here is some source code illustrating what I found to be an interesting use case of the factory pattern.

What arose from this design turned out to be a compact and uniform means to create heap allocated objects, and have their resources be managed by the Garbage Collector by default. In summary, I believe that design patterns can serve to ease the cognitive burden involved in designing complex systems, enabling programmers to translate their ideas into code more fluidly than they would otherwise be able to if they were forced to always come up with a new design. Don’t believe me? Just ask the chickens!

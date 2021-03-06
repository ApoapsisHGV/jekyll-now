---
layout: post
title: Schematic and PCB Design
lang: EN
ref: PCBDesign
categories: [cansat2018]
teaserImage: /images/posts/2018-05-01_CanSat_PCB_V1.png
---

After some time full of exams and tests we finally got to
take our next step: The PCB design.

### Step 1: Circuit diagram

Before you start printing a PCB (Printed Circuit Board), you have to design a circuit diagram (or: schematic diagram) which includes all the components and electrical connections you need in a properly arranged schema.

{% include post-figure.html path="/images/posts/2018-05-01_Erster_Schaltplan.jpg" caption="Our first schematic" %}

It's best to do it digitally, but it helps to have it all on paper as well.
The design tool we used is the web application EasyEDA, with which you can also convert schematics to PCB designs.
The electronics have been tested on breadboards before, so we could easily convert them into a schematic.

{% include post-figure.html path="/images/posts/2018-05-01_CanSat_Schaltplan.png" caption="Our schematic: each box represents a layer in the CanSat" %}

### Step 2: PCB design

After creating your wiring diagram you can go over to the PCB design.
Now you arrange all parts according to how it should look in the end.
You also have to consider how to arrange them, especially if you don't have a lot of space.
We decided to design three different PCBs which will be stacked in the CanSat.

{% include post-figure.html path="/images/posts/2018-05-01_CanSat_PCB_V1.png" caption="Our PCB design" %}

### Step 3: Paper printout

This step is not really necessary, but before you spend a lot of money on something that doesn't work in the end,
it may be worth it to print the finished design out on cardboard. Of course you can't test the electrical connections themselves, but you can see
if all the components fit on the board the way you wanted them to.
It's especially helpful for us since we can arrange all three parts the way we want to connect them in that CanSat.

{% include post-figure.html path="/images/posts/2018-05-01_CanSat_PCB_Layout.jpg" caption="For testing: All three layers printed on cardboard" %}

### And now?

We're almost done now. There are only a few things we want to optimize.
For example, we want to see if we can save a little more space by rearranging the components. Also, it would be helpful to have three
overlying holes with which we can connect the PCBs firmly together. And the antenna from the radio module
could be connected to the top PCB, so the antenna would be on top of the CanSat instead of in the middle.

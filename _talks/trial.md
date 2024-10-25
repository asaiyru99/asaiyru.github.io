---
title: "The Sweeter Sound of a Tube Amplifier"
collection: talks
type: "Tutorial"
permalink: /work/tubeamp
venue: null
date: 2019-03-01
location: null
---

Constructing a 20W Tube Amplifier because eBay DIY kits were not good enough.

<img src='/images/Tube1.jpg'>


In 2019, I learnt about D class amplifiers in college. Analog Microelectronics was hands down one of my favourite courses during college, right behind Digital Signal Processing. I ordered a tiny DIY D-class amplifier kit from Ebay  (3W, maybe 4 ohm impedance, if I recall correctly) and a soldering kit from the local electronics store. I found a Bluetooth audio module off of Amazon and started putting it all together. The instructions were clear and I didn't need to put much thought into it. I don't recall what IC chip this kit used though.

The audio quality never lived up to what I hoped it would. Then again, this was eBay.

My landlord had found out that I was starting a small audio-amplifier work station in my room and pitched the idea of valve amplifiers. I only learnt about BJTs and MOSFETs in college, so a valve amplifier itched my brain. Imagine, an amplifier with no IC chips, no transistors, only resistors, capacitors and vacuum tubes that performed the amplification.

So, I was using an old 7 tube Magnavox amplifier for reference, as demonstrated on wkinsler.com who has amazing electronics references! 
Out of the 7 tubes, two were for the pre-amplification stage and four for the amplification stage. I immediately stumbled upon the issue of the unavailability of the two pre-amplifier tubes called 6EU7s. I had to work with a 12AX7 and rewire it to be used as a substitute.

A quick Google search helped me find Miracle Electronics, who agreed to manufacture my transformers for me. Apparently, they provide transformers to the planes at HAL which is pretty cool. 

<h2>The First Run</h2>

In all honesty, the first attempt never comes out perfect. I messed up the wiring and fed positive feedback to the amplifier instead than negative. The amplifier sounded like an air raid siren and I panicked, worrying that it will blow up in my face.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Myj-aIommmA?si=Btv_vZaWS4-3g26k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h2>It Runs!</h2>

After the feedback issue was solved, it was finally playing music. I wouldn't say it sang like a canary, but that was probably because it had hardly warmed up. The wonderful thing about tube amplifiers is that they only sound better as time goes by. After running it for a few hours, the next day it sounded absolutely brilliant!

I contemplated implementing an audio equalizer to go with it, but I was already super happy with how well it sounded as is.

Some technical aspects:

This is a 20 W, 4 ohm amplifier that uses an E-I core power transformer (sec1: 600V CT 130ma, sec2: 5 volts 3 amps, sec 3: 6.3 volts 4 amps).

My tube line-up:

-12AX7-Left AF amp & phase inverter (Brand: Sovtek)

-12AX7-Right AF amp & phase inverter (Brand: Sovtek)

-6BQ5-Left output (Brand: JJ Electronics)

-6BQ5-Left output (Brand: JJ Electronics)

-6BQ5-Right output (Brand: JJ Electronics)

-6BQ5-Right output (Brand: JJ Electronics)

-5U4-G Rectifier (Brand: Electro-Harmonix)

I still have  my bill from Miracle Electronics! Haha

<img src='/images/bill.png'>


Note: I changed the secondary Z on the o/p transformer to 4 ohms.


<h2>Here's how it sounds: </h2>


<iframe width="560" height="315" src="https://www.youtube.com/embed/WKnQE7q7Vss?si=b6DvhDjPS1G32RbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

 

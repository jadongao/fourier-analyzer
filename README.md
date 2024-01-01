# LEGO Fourier Analyzer
A LEGO machine that presentation Fourier Analysis 

<div align=center> <img src='./overview.jpg' width = 40%/> </div>

# 1.What kinds of things is this work?

I made a LEGO machine that presentation Fourier Analysis in a high visual way. This machine replicates a Harmonic Analyzer designed in the late nineenth century by the physicist Albert Michelson.
It must be noted that I referred to the video of YouTuber @thoroughfareproduction who created a 5-element analyzer. I redesigned the gearbox to increase the number of elements to 7, and made my own improvements in the design of sinusoid generator gear set to make the operation smoother.

# 2.How to characterize / categorize this work?

LEGO machine, Fourier Analysis, Sinusoid, 3D models, Visual Learning

# 3.Briefly description of this work

A fourier analyzer can carry out two related tasks: it can add together weighted sines or cosines to produce a function graph, and it can perform the inverse operation of decomposing a given function graph into its constituent sinusoids. The addition of sinusoids is called Fourier synthesis and the inverse operation is called Fourier Analysis.
This type of machine is an analog computer that directly processes function graph without the digital computer which is almost considered essential by people today. It does not require electricity and can be operated by hand.
The capability of fourier analyzer depends on the number of elements. I tried to increase the number of elements to 7, while Albert Michelson's copper analyzer once achieved 80 elements.

## Example of fourier analysis

Taking Fourier synthesis (5 sinusoids elelemnt) as an example,

<!--![sinusoid function graph of computer](./computer%20function%20graph.jpg) -->
<div align=center> <img src='./computer%20function%20graph.jpg'> </div>

where $a_n$ is -1,+1, -1,+1, -1

F (x)= -sin(x)+sin(2x)-sin(3x)+sin(4x)-sin(5x)

Using this LEGO Fourier Analyzer, the actual output function graph is as follows, which is very close to the graph drawn by the computer.

<div align=center> <img src='./analyzer%20function%20graph.jpg' width = 50%/> </div>

## Parts of analyzer
This LEGO machine consists of the following parts:

<!--![parts of Analyzer](./overview%20with%20label.jpg)  -->
<div align=center> <img src='./overview%20with%20label.jpg' width = 80%/> </div>

### 3.1 Frequency generator
Frequency generator is a gearbox with 7 output shafts of different frequencies. The rotational speeds on the 7 axes are 1x, 2x, 3x, 4x, 5x, 6x, and 7x, respectively.
### 3.2 Sinusoid generator
The sinusoid generator is driven by 7  gears to drive Rocker arms, converting the circular rotation generated by the Frequency generator into sinusoidal motion. 
This combination of mechanical elements produces the seven different sinusoidal waves: sin(1x), sin(2x), sin(3x), sin(4x), sin(5x), sin(6x), sin(7x).

### 3.3 Ample bars, weight the sinoids
There are 7 sinusoidal motions weighted, namely $a_1$*sin(1x), $a_2$*sin(2x), $a_3$*sin(3x), $a_4$*sin(4x), $a_5$*sin(5x), $a_6$*sin(6x), $a_7$*sin(7x).
### 3.4 Summing lever
Summming lever at the top of the machine adds together the weighted sinoids
The Fourier Synthesis operation is completed by adding up all the weighted sinoids.
### 3.5 Platen and Plumb
The platen moves horizontally and plumb moves vertically. and the pen tied to plumb draws a function graph of the calculation result on the recording paper.

# 4.How do I make it?

Since March 2022, I have been exposed to the Harmonic Analyzer manufactured by physicist Albert Michelson for studying calculus and Fourier transform, and I am deeply attracted by its clever design. So I wanted to make one myself at home. The entire process took a considerable amount of time and effort to complete each component.

Sinusoid generator and Frequency generator are two key parts.

### The Frequency generator
The Frequency generator is a gearbox, and I am amazed by the clever design of Youtuber @ thoroughfareproduction. But because YouTuber only provided videos without detailed installation drawings, I couldn't see his internal design and had to explore it myself. I first completed a 5-axis gearbox like YouTube, and after completing it, my confidence doubled. I challenged and completed a 7-axis gearbox.

<!--![gear set](./frequency%20generator%20gear%20set.jpg) -->
<div align=center> <img src='./frequency%20generator%20gear%20set.jpg' width = 70%/> </div>

This machine using almost all types of LEGO gears: 8, 12, 16, 20, 24, 28, and 36 teeth gear. Since I don't have all of gear types at home, I also used a 3D printer to temporarily print several types. Later, the 3D printed parts were replaced with purchased LEGO parts, which made the operation more stable. This method of testing before formal procurement greatly improves production efficiency, eliminating the need to wait for several days to receive LEGO parts before testing.

### The Sinusoid generator
The Sinusoid generator uses LEGO worm gear to transmit circumferential rotation, but during the manufacturing process, there was a problem. Due to the loose gears and the fixed position of the worm, the worm would get stuck during operation, and the entire device could not operate at that time. I was forced to let go of this until a few months later when I had time to conduct a large number of repeated experiments and finally found a solution. The final method found is very simple, which is to make the worm position loose to avoid jamming. But in order to find this method, a large number of repeated disassembly and assembly were carried out.
The device that drives the LEGO beam to form sinusoidal motion is crucial. Youtubr @ thoroughfareproduction used a very simple bolt connection, but due to the need for rotation, a smooth bolt connection was used, which caused the gears and beam to shake easily. I believe this will cause significant errors, so I made improvements. Here, a 3D print model and bearings are used, and it is no longer a classic LEGO work.

<!--![gear-rod and bearing](./gear-rod%20and%20bearing%20with%20label.jpg)-->
<div align=center> <img src='./gear-rod%20and%20bearing%20with%20label.jpg' width = 50%/> </div>

<!--![sinusoid generator](./sinusoid%20generator%20gear-rod.jpg) -->
<div align=center> <img src='./sinusoid%20generator%20gear-rod.jpg' width = 50%/> </div>

# 5.Why do I make it?

When learning sound waves, I came across the idea that chords are composed of different combinations of sounds, and using Fourier Analysis, chords can be decomposed into the frequencies of their constituent sounds. I am very interested in Fourier Analysis, and I saw videos online from Professor Bill Hammack and YouTuber @ thoroughfareproduction, both dedicated to visualizing complex mathematical concepts in Fourier Analysis. So I decided to learn from them and make a LEGO machine myself.
When making this machine, I also traced the history of Fourier Analysis. I had a chance to communicate with these masters during this production process, and I felt their imaginative ideas in the era without electronic computers.


<table border="0">
 <tr>
    <td><b style="font-size:30px">Time</b></td>
    <td><b style="font-size:30px">Name</b></td>
    <td><b style="font-size:30px">Invention</b></td>
 </tr>
 <tr>
    <td>1807</td>
    <td>French mathematician and physicist Fourier </td>
    <td>He published a paper that using sine curves to describe temperature distribution：periodic functions can be represented by a series of cosines and sines.</td>
 </tr>
<tr>
    <td>1879</td>
    <td>Sir William Thomson (Lord Kelvin)</td>
    <td>He designed a 15 constituent sinusoids tide-predicting machine (TPM). </td>
</tr>
<tr>
    <td>1898</td>
    <td>Physicist Albert Michelson (Nobel Prizer) </td>
    <td>He designed the Harmonic Analyzer that calculates with 20 sinusoids. </td>
</tr>
<tr>
    <td>November 12, 2014</td>
    <td>Professor Bill Hammack </td>
    <td>He uses videos and PDF books to introduce Albert Michelson's Harmonic Analyzer. </td>
</tr>
<tr>
    <td>August 19, 2021</td>
    <td>Youtuber @thoroughfareproduction </td>
    <td>They desinged a wondrous LEGO contraption of gears, springs, levers and wheels to perform Fourier analysis. </td>
</tr>
</table>


# 6.What's the most meaningful thing you've made?

This LEGO machine can correspond one-to-one with mathematical formulas, which visualizes mathematical concepts and helps me understand them.

<!--![sinusoid generator](./math%20to%20machine.jpg)-->
<div align=center> <img src='./math%20to%20machine.jpg' width = 65%/> </div>


The production process of this machine was a perfect visual learning. It's very consistent with my experience as a tutor in a schoolhouse. The visual teaching method enables students to see and touch the abstract concepts they have learned, bringing students (including myself) closer to the abstract concepts.




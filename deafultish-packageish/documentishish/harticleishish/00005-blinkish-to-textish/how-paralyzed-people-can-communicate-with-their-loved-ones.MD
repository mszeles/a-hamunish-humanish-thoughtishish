From this article, you can learn **how you can get access to your brain from your app** for the price of a mid-level mobile phone by buying an EEG band and an app with which you can get the raw EEG data from the band.

I will lead you through the development of an app with which you can detect eyeblinks using a Muse S EEG band. We will convert the eyeblinks to text using the Morse code as a result we will have a solution with which completely paralyzed people can communicate with their loved ones.

I will also demonstrate **how you can build an app in pure Python with the aid of Kivy** resulting in a program that can be packed to Android, iOS, Windows, Mac, and Linux.

Before we start coding, please let me share some moments from my life which led me to start tinkering with my brain.

## The Backstory

### My First Contact With Brainwaves
Let's move back 30 years in time.

I was in my room, sitting in front of my Commodore 64 computer. My brother had already moved out by that time, but I was not alone, as my friend Szabi was also with me.

I loved computer games. Playing games like Ugh Olympics, Pirates, Defender of The Crown, Boulder Dash, Wizard of Wor, Nebulus, and Bruce Lee gave me more pleasure than anything else in the world.

At that time I was playing a newly discovered game called Benji. I was trying to figure out how I can play the game with little success.

Suddenly I saw something in the corner of my eye so I turned right to look through the window. There was nothing unusual except one thing.

A black figure was floating in the air above the roof of our garage.

I got scared as hell so I asked Szabi whether he also saw the figure or not.

No! There is nothing there. - he replied.

Szabi went downstairs to tell my parents what had happened to me. My parents come up in a hurry and they quickly realized something is not ok, so they saw me down in the living room.

I remember they asked what was my name. I started to think, but I couldn't answer as I couldn't recall it. The feeling I felt at that moment when I couldn't recall my name has been burnt into my mind for eternity.

From this point, I couldn't recall anything as I lost my consciousness. Just a few seconds after my parents called the doctor my whole body started to shake unstoppably.

That was the first time when I had an epileptic seizure.

My next memory is being in a room in the hospital. A nurse lubricated small thingies with a cold gel, then she put a very strange hat on my head.

The hat was strange as many wires were coming out of it all of them connected to a machine.

I had to lay down and stay calm, then the machine drew lines on a piece of paper.

As I found out later those were my brainwaves and the machine was an electroencephalography (EEG) device. I couldn't understand the EEG diagram but based on what I heard they looked pretty bad back then.

A couple of days later I was allowed to go home.

I was not allowed to play on computers, or watch TV and I couldn't go to the disco with my friends.

From that point, fear became my and my family's best friend as we could never know when another epileptic seizure will come.

During the upcoming years, I had to take medicines and I also had to visit the hospital many times to have regular checkups with a neurologist. During these visits, I started to form a friendship with this EEG device. Month by month my EEG results became better and better.

I can still remember the smell of the room, the feeling of the cold gel, the long wires, the little diodes, the strange hat, and the EEG curves painted on paper.

I never had another epileptic seizure again and after 3 years my neurologist told me I recovered.

## My Second Contact With Brainwaves
The year is 1994, just 2 years after my epileptic seizure. My parents enrolled me and my brother Tomi in a Silva Mind Control for kids course.

I have very little memory, but I do remember that was the time when I heard about delta, theta, alpha, and beta brainwaves. I have not just heard about them but in theory, I also learned how to control the brainwaves by relaxation.

4 years later I visited the Silva Mind Control training with my friend Edit. By then I was able to understand and learn many techniques which were thought there.

Even if none of the magical techniques work I still learned about peg lists and relaxation.

In reality, I used the other techniques and I do believe they worked, but as I had no parallel life (at least I am not aware of that) in which I could live the same life without doing the Silva course, I cannot tell if my achievements were really related to those techniques.

There was one huge problem with the relaxation:

I couldn't tell if I was really in alpha or not.

Two years later I went to the Budapest University of Technology (BME) and I became a scientistish.

For me scientistish means I do not believe in anything except it was proven by science. Thanks to this I was sure all the Silva methods are fake similar to all the other supernatural things I have heard of.

## My Third Contact With Brainwaves
24 years later we arrive in the present. During the last years, I went through an emotional rollercoaster. I had so deep depression I was sure I lose my job, my flat, my family leaves me, I became homeless and I will even be bad for a homeless and I die in a couple of days.

I know it sounds funny, but that was my reality back then.

It took me 2 psychologists, 2 psichoterapeut a RED EQ trainer, and the support of my family and friends, but finally, I managed to come back.

This experience has changed my life forever. I am currently re-reading Eckhart Tolle's The Power of Now Book and I do see some similarities between his life and my life. However, I did not become homeless in reality I was homeless in my mind. Now I understand much more from that book.

Also by now, I became a hscienistish. Hscientistish means I do believe in what humans say and I try to verify it by talking to that person and using somewhat scientific techniques.

I cannot tell exactly what was the trigger, but I decided to order a Muse EEG band and examine my brainwaves during experimenting with different meditation and relaxation techniques to find out which works and which does not.

My Muse S arrived 3 weeks ago, but before it arrived I already came up with an idea in which I can combine programming and my brainwaves. Before I get to the point, please let me tell you about how I got inspired to implement my first mind-controlled app.

## The Inspiration
I was googling different apps developed for the Muse band but I had to realize there are almost no apps, or at least it is not easy to find them via Google. Luckily I found an article from [Anush Mutyala](https://anushmutyala.medium.com/) with the title [Muse 101 — How to start Developing with the Muse 2 right now](https://anushmutyala.medium.com/muse-101-how-to-start-developing-with-the-muse-2-right-now-a1b87119be5c).

Anush has developed a hands-free slideshow that can be navigated by using eyeblinks. He was also able to switch Chrome tabs using eyeblinks and scrolling via measuring the focus/concentration of the user using only the raw EEG data. He even made a video summarizing solutions built on brainwaves.

In addition to Anush's article

So in the end it was Anush Mutyala, who inspired me to develop my own app(s).

## The Idea
After reading Anush's article, my brain started to spin and after thinking for quite a while I came up with the eye













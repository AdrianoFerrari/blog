---
title: "A Habit System with Consistency & Flexibility"
date: 2019-07-18T09:06:12-04:00
blackfriday:
  extensions:
  - footnotes
draft: true
---
# Backstory

I recently found my New Year's Resolutions from 1999, at age 15.<br>Across the top I wrote "1999 will be great if I follow these rules" (*Spoiler Alert: I didn't*).

{{< figure src="resolutions-1999.jpg" width="500px" >}}

There was a lot for me to parse in this list, including my atrocious handwriting. But one thing stood out to me:

> After 20 years, my resolution to write short stories regularly is *still unmet*.

Ouch! That's a depressing thought [^1].

And it's not for lack of trying. For all the habits I've tried to form since, I used dozens of popular habit-forming techniques, with hundreds of variations each. From Seinfeld chains to Mini-habits, as well as larger systems like GTD, Autofocus, and apps like Beeminder, Habitica, Loop, and many *many* others than I can't remember. I've even developed and sold my own habit-tracking software [^2].

But none of them would ever stick.

Until now, that is. I've been using the same system for 18 months [^3]. More importantly, the nagging sense of doubt about whether it's the "right" system for me is gone, and I can now focus not on *how* to achieve my goals, but on *what* those goals should be.

All it took was to realize what critical piece was missing from other systems, and fill in that gap.

## The Dilemma
After much journaling and reflection, I came to a realization : 

> As a struggling perfectionist, and as a generalist, I was *afraid* of suceeding at the "wrong" habit!

Rationally I know that not choosing is worse that choosing incorrectly. I also know that no matter what, I can always change my mind later.

But therein lies the problem. The only way to change my mind was by abandoning the system, or admitting defeat and starting over. In other words, to change you have to go through failure : either break a streak or delete the habit.

Doing that lowered my confidence in that particular system, and in myself. Worse, I'd been in this cycle so many times that I eventually became afraid of even starting a committment (for fear of failing yet again).

Habits, by definition, require consistency. But to ease my fears, and allow for adaptation, I require flexibility. This dilemma is captured by these two opposing views, both of which are deeply true:

---

> "A foolish consistency is the hobgoblin of little minds, adored by little statesmen and philosophers and divines... Speak what you think now in hard words, and tomorrow speak what tomorrow thinks in hard words again, though it contradict every thing you said today."<br>
> &mdash; *Ralph Waldo Emerson, Self-Reliance*

---

> "Nothing hinders a cure so much as frequent changes of treatment; a wound will not heal over if it is being made the subject of experiments with different ointments; a plant which is frequently moved never grows strong. Nothing is so useful that it can be of any service in the mere passing."<br>
> &mdash; *Seneca, Letter II*

---

In other words, only a fool values consistency for its own sake. When discovering that a certain consistency isn't valuable, the right thing to do is to change. But then again, **it takes time to discover if something is valuable or not**, so don't change too hastily.


Once I phrased the dilemma in this way, the resolution was relatively easy. I just had to pluck two ideas from habit systems I've seen where flexibility is inherent to their designs.

## Design Principle 1 - Delayed Flexibility
> To have both flexibility and consistency, simply introduce a *delay* between the *decision* to change and the *act* of changing.

This is a simple idea, but incredibly powerful. The delay removes the instant gratification that changing often provides.

In my case, it could look like this :

`"Sure, you can stop writing and start a programming habit instead. But only as of 16 days from now."`

To drop my writing habit in this scenario, I'd have to believe for *16 days in a row*, that I'm deriving *no value* from my daily writing. This neatly resolves the tension : I *can* change, but I must *wait*. If the desire to change is a result of "shiny-object syndrome" rather than any inherent issues with my current habit, I end up keeping the habit. If it turns out that it actually is a foolish consistency, then I just wait a few days and I'm off the hook, guilt-free.

I won't go into more detail, since the originators of this idea have done so many times. I encourage you to check out their writing on what they call the "[Akrasia Horizon](https://blog.beeminder.com/flexbind/)", if you're interested in the concept.

## Design Principle 2 - Fault Tolerance
> "100% commitment is a breeze, 99% is a bitch."
> <br> - *Jack Canfield (attributed)*

**I call bullshit** on that. It's this perfectionist mentality that makes it frightening to even start habits. If I have to commit to a perfect success rate, then I'll aim very low and stay there.

Perfect winning streaks and "Seinfeld chains" are fantastic motivation. But breaking a streak is instant demotivation.

Instead, I take inspiration from Ben Franklin and his "13 virtues". Each week he would focus on improving one virtue, but *allow himself to fail* on the other 12.

In my system, I allow myself *3 slip ups* for each habit. These "allowed failures" regenerate at ever-slowing rates. So I have more allowed failures when the habit is new, and fewer as time goes on.


# The "Kernel Card" System

The Kernel Card system is the core of my entire productivity operating system [^4]. It's simple, and takes me around 5 minutes a day to maintain.

Every morning:

1. I take yesterday's card as reference...
2. and copy the habits over to a blank index card...
3. along with any changes that I'm allowed to make.

Here's an example of my card from `2019-07-XX`:

[img]

The key to this, and what makes it so much more than a daily habit checklist, is in the rules around the "metadata" that each habit carries with it:

```ruby
[ ] 10 pushups or more  (8-6,   2/3   :   7-30)
   |------------------| |---|  |---|     |----|
    Habit Name          Delay  Allowed   Failure
                        Date   Failures  Recovery
```
The "Delay Date" is updated every day (up to a max of 3 months). Allowed failures are updated when I fail, and when I get to recover an allowed failure.

There are rules on *adding habits*, *continuing habits*, *dropping habits*, *failing*, and *recovering from failure*.

## Adding a New Habit

{{< figure src="kernel-card-add-rule.png" >}}

## Continuing a Habit

{{< figure src="kernel-card-continue-rule.png" >}}

## Allowed Failure

{{< figure src="kernel-card-fail-rule.png" >}}

## Recovering from Failure

{{< figure src="kernel-card-fail-refresh-rule.png" >}}

## Dropping a Habit

{{< figure src="kernel-card-drop-init-rule.png" >}}

{{< figure src="kernel-card-drop-do-rule.png" >}}

---

## Footnotes
[^1] : When I first saw this list, I felt sad and disappointed. My wife helped me see that in fact, I *have* achieved many of the goals listed. And for writing and exercise, knowing that they've been goals of mine since then can be seen as reinforcing how important they are to me. That's a good reminder for when I start to doubt that.


[^2] : The now defunct "HabitShaper" : https://www.youtube.com/watch?v=Wzlw-vrG1-E

[^3] : Not impressed? That's *6 times longer* than any other system I've used or designed.

[^4] : A [kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)) is the core of a computer's operating system, and one of the first programs to load. Sticklers might argue that a "[bootloader](https://en.wikipedia.org/wiki/Booting#Modern_boot_loaders)" would be a more accurate analogy for my card system, but I argue that it's close enough and "kernel" sounds better.

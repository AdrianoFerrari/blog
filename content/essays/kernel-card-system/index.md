---
title: "A Habit System for Consistency & Flexibility"
date: 2019-07-18T09:06:12-04:00
blackfriday:
  extensions:
  - footnotes
draft: true
---
I recently found my New Year's Resolutions from when I was 15 years old.<br>Across the top I wrote "1999 will be great if I follow these rules" (*Spoiler Alert: I didn't*).

{{< figure src="resolutions-1999.jpg" width="500px" >}}

There was a lot for me to parse in this list, including my atrocious handwriting. But one thing stood out to me:

> After 20 years, my resolution to write short stories regularly is *still unmet*.

Ouch! That's a depressing thought [^1].

And it's not for lack of trying. For all the habits I've tried to form since, I used dozens of popular habit-forming techniques, with hundreds of variations each. From Seinfeld chains to Mini-habits, as well as larger systems like GTD, Autofocus, and apps like Beeminder, Habitica, Loop, and many *many* others than I can't remember. I've even developed and sold my own habit-tracking software [^2].

> But none of them would ever stick. Until now.

I've been using the same system for 18 months [^3]. More importantly, the nagging sense of doubt about whether it's the "right" system for me is gone, and I can now focus not on *how* to achieve my goals, but on *what* those goals should be.

All it took was to realize what critical piece was missing from other systems, and fill in that gap. As typical of a designer, I would love to go into meticulous detail as to why I designed it the way I did, and why I believe it works so well...

But, I'll give you the solution first, and leave those self-indulgent musings till afterwards ;).

# The "Kernel Card" System

The Kernel Card system is the core of my productivity operating system [^4]. It's simple, uses only pen and index cards, and takes me around 5 minutes a day to maintain.

Every morning:

1. I take yesterday's card as reference...
2. and copy the habits over to a blank card...
3. along with any changes that I'm allowed to make.

Here's an example of my card from `2019-07-XX`:

[img]

The key to this, and what makes it so much more than a daily habit checklist, is the "metadata" that each habit carries with it:

```ruby
[ ] 10 pushups or more  (8-6,   2/3   :   7-30)
   |------------------| |---|  |---|     |----|
    Habit Name          Delay  Allowed   Failure
                        Date   Failures  Recovery
```
**Habit Name** : A short but *unambiguous* description of what constitutes success for this habit. It should be binary: "Did I do it, or not?"

**Delay Date** : This is the earliest date at which you can change the habit, or drop it. This date is pushed further into the future every day, as described in "Continuing a Habit" below.

**Allowed Failures** : The number of allowed failures you have left. This decreases any time you fail, and increases when you are allowed a "failure recovery".

**Failure Recovery** : This is the date when you get an allowed failure back. The date is set as the Delay Date of the day when you failed, as described in "Recovering from Failure" below.

There are rules on *adding habits*, *continuing habits*, *dropping habits*, *failing*, and *recovering from failure*.

### Adding a New Habit

Adding a new habit is as simple as writing it out, and setting the **Delay Date** to be `(today) + 2`, and the allowed failures at `3/3` (or whatever your chosen default is):

{{< figure src="kernel-card-add-rule.png" >}}

### Continuing a Habit

Every day, copy over the habits that you have, and add `2` to the **Delay Date**:
{{< figure src="kernel-card-continue-rule.png" >}}

### Allowed Failure

When *(not if)* you slip up with your habit, you mark it with an `X`, and on the following day copy it over with one fewer **Allowed Failure**. You also copy over the **Delay Date** from the day you failed. This becomes the date that you will "recover" from this failure:

{{< figure src="kernel-card-fail-rule.png" >}}

### Recovering from Failure

If you're copying a habit over from yesterday, and see that one of the **Allowed Failure** recovery dates is equal to today, then you increase the **Allowed Failure** count, and remove that recovery date:

{{< figure src="kernel-card-fail-refresh-rule.png" >}}

### Dropping a Habit
If you decide to drop a habit, simply copy it over and add `drop (current Delay Date)` to it:
{{< figure src="kernel-card-drop-init-rule.png" >}}

If a drop date arrives, **and the drop note is still there**, you can drop the habit:

{{< figure src="kernel-card-drop-do-rule.png" >}}

# Why It Works

## Flexibility

With the Delay Date system, there's a built-in/guilt-free way to *change your mind* about what you choose to do.

This addresses the key fear that was underlying my previous attempts. As a struggling perfectionist, I was *afraid* of succeeding at the "wrong" habit!

In every other system I'd tried, the only way to change my mind was by abandoning the system, or admitting defeat and starting over. In other words, to change you have to go through a system failure : either break a streak or scrap the habit.

Doing that lowered my confidence in that particular system, and in myself. Worse, I'd been in this cycle so many times that I eventually became afraid of even starting a committment (for fear of failing yet again).

But it's also entirely rational to want a system to be flexible. I'd been through a great number of life changes, and I knew that sticking to old behaviors and goals wasn't always sensible. It's important not to get stuck in "foolish consistencies":

> "A foolish consistency is the hobgoblin of little minds, adored by little statesmen and philosophers and divines... Speak what you think now in hard words, and tomorrow speak what tomorrow thinks in hard words again, though it contradict every thing you said today."<br>
> &mdash; *Ralph Waldo Emerson, Self-Reliance*

---

## Consistency

But isn't a habit-forming system that allows you to change your mind a *total contradiction*?

It's true that only a fool values consistency for its own sake. When discovering that a certain consistency isn't valuable, the right thing to do is to change. But then again, **it takes time to discover if something is valuable or not**:


> "Nothing hinders a cure so much as frequent changes of treatment; a wound will not heal over if it is being made the subject of experiments with different ointments; a plant which is frequently moved never grows strong. Nothing is so useful that it can be of any service in the mere passing."<br>
> &mdash; *Seneca, Letter II*

---


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


---

## Footnotes
[^1] : When I first saw this list, I felt sad and disappointed. My wife helped me see that in fact, I *have* achieved many of the goals listed. And for writing and exercise, knowing that they've been goals of mine since then can be seen as reinforcing how important they are to me. That's a good reminder for when I start to doubt that.


[^2] : The now defunct "HabitShaper" : https://www.youtube.com/watch?v=Wzlw-vrG1-E

[^3] : Not impressed? That's *6 times longer* than any other system I've used or designed.

[^4] : A [kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)) is the core of a computer's operating system, and one of the first programs to load. Sticklers might argue that a "[bootloader](https://en.wikipedia.org/wiki/Booting#Modern_boot_loaders)" would be a more accurate analogy for my card system, but I argue that it's close enough and "kernel" sounds better.

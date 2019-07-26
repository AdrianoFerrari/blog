---
title: "A Habit System for Consistency & Flexibility"
date: 2019-07-18T09:06:12-04:00
blackfriday:
  extensions:
  - footnotes
draft: true
---
# Backstory
I've been hopping from one productivity system to another for years:

* Seinfeld Chains
* GTD
* Autofocus
* Final Version
* Mini-habits
* Unscheduling
* The One Thing
* Weighted random sampling
* HabitBull
* Beeminder
* *and many, many more*

I've even designed my own productivity software. "[HabitShaper](https://www.youtube.com/watch?v=Wzlw-vrG1-E)", which is now abandonded. And "Stride", a task manager based on how CPU's juggle and complete tasks, which *\*ahem\** I never completed.

All this leap-frogging has just been perfectionism, of course. I know that more important than which system I choose is **whether I stick to any system** long enough to see the benefits. Seneca said it best:

> "Nothing hinders a cure so much as frequent changes of treatment; a wound will not heal over if it is being made the subject of experiments with different ointments; a plant which is frequently moved never grows strong. Nothing is so useful that it can be of any service in the mere passing."<br>
> &mdash; *Seneca, Letter II*

*How bad has it been, really?*<br>
Well, I recently found my New Year's resolutions from when I was 15:

<!--more-->

{{< figure src="resolutions-1999.jpg" width="500px" >}}

There was a lot for me to parse in this list, including my atrocious handwriting. But one thing was clear to me:

{{% hltext %}}Writing short stories regularly has been a goal of mine for decades, yet in that time my longest streak has been around 3 months.{{% /hltext %}}

It wasn't until 2017 that I finally created a system I could stick to. I've now been using it for the last 18 months, which is *6 times longer* than any other I've used or designed. And it has worked despite living through one of the most difficult times we've had as a family.

How did I finally manage to achieve consistency?<br>
The key was realizing that I over all these years, I was focusing on **exactly the wrong thing**...


## The Complement to Consistency

In Systems Thinking it's said that people often know which lever would have the biggest impact on a system. The problem is that they tend to want to push that lever very hard *in the wrong direction*. Economic growth is important, but we should aim for *less* of it, for instance[^1].

In my constant quest for consistency, I was doing the same thing.

{{% hltext %}}What was missing for me wasn't *more consistency*, it was *more flexibility*.{{% /hltext %}}

In every other system I'd tried, the only way to change my mind was by admitting defeat and starting over, or by abandoning the system altogether. In other words, to change you have to go through a system failure : either **break a streak** or **give up on the habit**.

Doing that lowered my confidence in that particular system, and in myself. Worse, I'd been in this cycle so many times that I eventually became afraid of even *starting* a committment (for fear of failing yet again).

Perfectionism aside, it's also entirely *rational* to want a system to be flexible. I've been through a great number of life changes, and I know that sticking to old behaviors and goals isn't always sensible. It's important not to get stuck in "foolish consistencies":

> "A foolish consistency is the hobgoblin of little minds, adored by little statesmen and philosophers and divines... Speak what you think now in hard words, and tomorrow speak what tomorrow thinks in hard words again, though it contradict every thing you said today."<br>
> &mdash; *Ralph Waldo Emerson, Self-Reliance*


But isn't a habit-forming system that allows you to change your mind at will a *total contradiction*?<br>
Not necessarily. With two simple ideas, we can have both.

### Flexibility to Change

{{% hltext %}}To have both flexibility and consistency, simply introduce a *delay* between the *decision* to change and the *act* of changing.{{% /hltext %}}

In the old mode, I would make a lot of impulsive changes based on "shiny object syndrome". Introducing a delay between decision and action removes the instant gratification of changing.

For example, say that I've been chugging along in my writing, and suddenly I discover a new programming language. I try it out and feel immensely powerful. I begin to doubt my identity as a writer:

*"Do I really want to keep writing every day? It's clear to me now... I'm a __programmer__ at heart!"*

The system has an answer for me:

*"Sure, you are free to quit your writing habit and start a programming one instead. __But only if you wait 24 days__."*

So now, in order to drop my writing habit, I'd have to believe for *24 days in a row* that I'm deriving *no value* from my daily writing. This neatly resolves the tension : I *can* change, but I must *wait*. If the desire to change is a result of "shiny object syndrome" rather than any inherent issues with my current habit, I end up keeping the habit. If it turns out that it actually *is* a foolish consistency, then I just wait the prescribed number of days and I'm off the hook *guilt-free*.

I won't go into more detail, since the originators of this idea have done so many times. I encourage you to check out their writing on what they call the "[Akrasia Horizon](https://blog.beeminder.com/flexbind/)", if you're interested in the concept.

### Flexibility to Fail

{{% hltext %}}To handle failure, allow a *specific number* of failures within a given *timeframe*.{{% /hltext %}}

By pairing these "Allowed Failures" with the "Delay Date" idea above, we can also grow the timeframe slowly, so that your habits are lenient at first, but become more strict as time goes on.

An important element of this, as we'll see, is that once you recover completely from a failure or slip-up, there is *no record of it* going forward.

---

With these two methods, we can design a system that has a balance between consistency and flexibility:


# The "Kernel Card" System

## Overview

The Kernel Card system is the core of my productivity operating system. It's simple, uses only pen and paper, and takes me around 5 minutes a day to maintain.

Every morning:

1. I take yesterday's card as reference...
2. and copy the habits over to a blank card...
3. along with any changes that I'm allowed to make.

Here's an example of my card from `2019-07-05`:

{{< figure src="kernel-card-example.jpg" width="500px">}}

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

## Rules

There are rules on *adding habits*, *continuing habits*, *dropping habits*, *failing*, and *recovering from failure*.

### Adding a New Habit

Adding a new habit is as simple as writing it out, and setting the **Delay Date** to be `today + 2`, and the allowed failures at `3/3` (or whatever your chosen default is):

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


## Why it Works

[Discussion]
Why I believe it works. What could be improved

[Conclusion]
It's a container for any other system. Goal is sto stick longer. Result is more important : self-efficacy... or "Trust that I can keep promises to myself."


---


[^1] : This, and other counterintuive results, are explained in "Thinking in Systems : A Primer".


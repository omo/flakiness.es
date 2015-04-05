+++
date = "2015-04-05"
draft = false
title = "Truck Factor 0.5"
+++

A few months ago, I asked Yuko, my wife, to create an launcher icon for an Android app I was working on.
It's one of my side projects. I wanted the icon because
I was going to upload the app to Play Store and
I knew she had some good visual design skills.

She agreed, but it turned out that she had busy weeks coming. 
I was waiting, waiting and waiting, and then distracted other things.
She couldn't make it, and the development stalled there.

This made me wonder: Why does the collaboration, which intuitively should help the progress, sometimes hinder it?
We all see this happening time to time. Even I did once block my friend's project years ago where I was working on the backend. I gave it up as my day job got busy, and it killed our (well, his) project.

Another observation here is that the blockage happens more on a side project than a day job. Apparently the collaboration goes well more at work than at weekends. Even so,
some people [recommend](http://programmer-hek.blogspot.com/2014/11/as-programmers-why-we-never-finish-our.html) to have side projects with others.
We should be better collaborators of our side projects.

## Truck Factor

There is a notion of "[Truck Factor](http://en.wikipedia.org/wiki/Bus_factor)" of a software project. Wikipedia tells that it is *the number of key developers who would need to be incapacitated to make a project unable to proceed*. It is the number, the bigger the better.

For single-person projects, obviously the factor is one. That is you who can make the project incapable. What about a duo-project where, to say, one is working on the frontend and another is on the backend?
If following the definition, the factor is same - one. It however is clearly worse than a single-person project: Either of you can make it incapable.

Speaking in a system language, a single-person project has one "[SPOF](http://en.wikipedia.org/wiki/Single_point_of_failure)",
but duo-project like above has two. The latter is worse.

I would name this situation *Truck Factor 0.5*. This is bad news for side project owners.
Side projects themselves are almost already fragile enough, and you'll weaken them further if you get someone to help. It's the last thing you expect to happen.
How can we do better here? Is it possible to collaborate and strengthen the truck factor?

## 1.01

A modern open-source way with GitHub is a possible choice.
You open your project to public, push the repo, file the bugs, then someone might come to help fix these bugs, or even better, bring one's own ideas and code to the project.

One virtue of this model is that you don't have to rely on these unexpected contributors. The truck factor won't go down.

At the same time, it doesn't raise the number much either. For many side projects, it's rare to have such external contributions. So for the most of them, the truck factor is something like 1.01. Although this is slightly better than 1.0, isn't there any better way?

## Not Like a Day Job

Imagine you have a friend who is willing to collaborate with you on a side project and you two are going to start new one together. What should you do?

If this is a day job, you'll sketch some rough architecture and split the work between members based on the blueprint. This doesn't seem a great way for side projects though. Unlike professional work with strong commitment, personal projects are vulnerable. Procrastinations and distractions of the participants are likely. Having two SPOFs, the result of the work split, will be too much burden.

What about the open source 1.01 model above? The problem is that it isn't trivial to decide who is 1.0 and who else is 0.1. If you both want to be 1.0, there will be many conflicts.

Being the 1.0 means making key decisions: Which languages/frameworks to use, which part to take, where to start... There is endless list of sweet decisions. Having conflicts over these will kill the project. This is different kind of failure than hitting by a boredom truck. It is killed by opinions, egos or self-expressions if you prefer a gentle word.

## Be a 0.8

Probably I should throw my ego away and focus on helping projects of others. I do it indeed, and I'm happy about that. Writing patches to someone's cool projects is satisfactory in its own ways. It's grateful to hear a little appreciation and see my name in the commit log.

At the same time though, I want to have my own project, where I have freedom, make decisions, step on the greenfield as a frontrunner. This cannot be done in any non-small project unless you are a rockstar. And most of cool projects have the certain size and you aren't the rockstar.

And here is the extra hope: I want to share this joy of the greenfield with my friends. But I have no clue how. Here we arrived at the "Truck Factor Greater Than 1.0" question.

Talking in the context of Truck Factor, I want some middle ground between single-person projects with TF=1 and established projects with TF>2.
Probably I want to be a 0.8 of a TF=1.8 project. I have to learn and experiment how to become that one.

One of things I haven't tried is to help someone else's single-person project - I've been arrogant enough not to have done that. I'm not sure it satisfies my ego or desire for self-expression or whatever. I'm not sure if it annoys the author or helps him/her either.

But I'm sure I'll learn something from it.

### P.S.

Yuko finally made a great icon for me last week. It was far more well done than I hoped. Now it's my turn to finish the app for her icon. "I didn't know you were waiting!" She said. The truck didn't hit her - It just kidnapped her for a while and I had not searched for her.


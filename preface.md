# Introduction

## Number Go Up

There is a particular kind of moment that happens in corporate meetings. Someone puts a chart on the screen. The line is going up and to the right. Everyone nods.

This is good.

It almost doesn't matter what the line represents. Revenue is up. Customer engagement is up. Bugs closed are up. Productivity is up. AI adoption is up. Whatever we have decided should be going up is, in fact, going up.

Success.

I've been in software engineering for a over 26 years. Lately, one of the numbers everyone wants to see going up is AI usage. Companies are spending enormous amounts of money on artificial intelligence, and understandably, they'd like to know whether anyone is actually using it. So we measure things. How many employees are interacting with AI? How frequently? How many tokens are they consuming? How many workflows incorporate it? We put those numbers on dashboards and watch what happens.

Number go up.

Excellent.

Except there is an irritating question lurking underneath all of this:

**Did anything actually get better?**

Maybe it did.

That's important. I'm not suggesting that AI usage is meaningless, or that every executive looking at an adoption dashboard has been hypnotized by Microsoft Excel. If people are finding genuinely useful ways to incorporate AI into their work, we'd expect usage to increase. The rising number might be telling us something valuable.

But it might not.

An employee could use an AI assistant fifty times today and accomplish very little. Another could use it once, solve a problem that would otherwise have taken three days, and go home early. If we're measuring interactions, the first employee wins. If we're measuring tokens, maybe the person who wrote the worst prompts wins. If we're measuring adoption, simply opening the tool might be enough to make the dashboard happy.

And this is where things get interesting.

The moment people know that AI usage is being measured, AI usage stops being merely something we're observing. It becomes something people know they're *supposed to do*.

Those are not the same thing.

Now the engineer who doesn't think AI is particularly useful for the task in front of her has another consideration. She can do the work the way she believes is best, or she can find some way to involve AI because the organization has made it clear that AI usage is desirable.

Maybe she asks it to summarize something she already understands.

Maybe she generates some code she could have written herself.

Maybe she interacts with it just enough that the appropriate systems register the fact that, yes, this employee is participating in the glorious AI revolution.

The dashboard sees another successful adoption.

Number go up.

This isn't really a book about AI. AI just happens to provide a wonderfully current example of something human beings have been doing for a very long time.

We want to know whether something is working.

The thing we actually care about is complicated, messy, subjective, or difficult to observe. So we find something we *can* observe. We count it. We track it. We put it on a chart.

And at first, the number helps us see.

Then, almost imperceptibly, something changes.

We stop asking whether the number is telling us that things are getting better.

We start asking how to make the number better.

That difference is what this book is about.

## Hi. I’m an Engineer. We Measure Things.

Before I sound too critical of the people building these dashboards, I should probably introduce myself.

I'm a software engineer.

We measure things.

This is not a criticism. Measurement is one of the ways engineering works. If I make a change that's supposed to improve performance, I don't want to stare thoughtfully at the computer and ask whether it *feels* faster. I want numbers. How long did it take before? How long does it take now? How much memory are we using? How often does it fail? Give me the data.

Numbers are extraordinarily good at cutting through our ability to fool ourselves.

The problem is that measuring the software is often much easier than measuring the people who create it.

Imagine that you manage a team of software engineers and someone asks a perfectly reasonable question: How productive is your team?

Good question.

Now answer it.

You could count lines of code. More code means more productivity. Except sometimes the best engineering work involves deleting code. I've had changes where removing something was the entire point. Presumably I should not have to report negative productivity for making the product better.

So maybe we count commits.

That seems better. A commit represents a completed unit of work. Except one engineer might make twenty small commits while another makes two large ones. Neither tells you much about what was accomplished. And once you start rewarding commits, I assure you that engineers possess the technical ability to produce more commits.

We could count bugs fixed.

Now we're getting somewhere. Bugs are bad. Fixing bugs is good. Therefore, more bugs fixed must be better.

You may already see where this is going.

We could measure features completed, milestones reached, story points burned down, schedules met, code reviews performed, customer issues resolved, tests written, or any of the other artifacts software development leaves behind. Every one of these tells us something.

That's what makes this difficult.

Bad metrics aren't necessarily useless metrics.

Lines of code really can tell you something about what is happening in a codebase. Commits really can tell you something about development activity. Bugs closed really can tell you something about maintenance work. AI interactions really can tell you something about AI adoption.

The problem begins with the word *something*.

What the organization usually wants to know is much bigger:

**Are we doing good work?**

Are we building the right thing? Is the software reliable? Will another engineer be able to understand it six months from now? Did we solve the customer's problem? Did we make thoughtful architectural choices? Did someone notice the dangerous assumption everyone else had overlooked? Did an engineer spend three days thinking about a problem and eventually realize that the best solution was to change six lines?

Those things are harder to put on a dashboard.

So we reach for the things that are easier.

I've spent enough time in software engineering to have been on both sides of this problem. I've looked at measurements because I needed to understand what was happening. I've also been the person whose work was being translated into measurements.

Those are very different experiences.

From one side, a metric looks like information.

From the other, it can feel like judgment.

And the distance between those two perspectives matters.

A manager may look at a dashboard and see a useful signal. An engineer may look at the same dashboard and immediately think of five reasons why the number doesn't mean what everyone thinks it means. Neither person necessarily has bad intentions. They're simply standing in different places.

This is one of the tensions we'll keep returning to throughout this book.

The people doing the measuring need some way to understand a complicated reality they cannot observe directly. The people being measured live inside that reality and can see all the details the measurement leaves out.

Both perspectives contain information.

Both can also be wrong.

That's why I don't want to write a book arguing that metrics are stupid. That would be easy, satisfying, and wrong. Metrics have tremendous value. I use them every day.

The harder question is how much authority we give them.

Because most measurements aren't the thing we actually care about. They're a stand-in for it. A proxy. A little numerical window through which we try to glimpse something much larger.

And there's nothing wrong with looking through the window.

The trouble starts when we forget there's a world on the other side.

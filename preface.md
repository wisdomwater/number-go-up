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

## Engineers Have a Highly Refined Bullshit Detector

One of the occupational hazards of being an engineer is that you develop a fairly sensitive bullshit detector.

I don't mean that engineers are uniquely wise. Spend enough time with us and that theory will collapse quickly.

I mean that we're trained to look at systems and ask how they break.

Give an engineer a process and we'll find the edge cases. Give us a rule and we'll ask what happens when two rules contradict each other. Give us a metric and, whether intentionally or not, we'll eventually figure out how to make the number go up.

This can create some interesting situations.

Years ago, I worked with an engineer who was known for getting things done quickly. He moved fast. He wrote code. He delivered. There was always activity around him, and activity is wonderfully visible.

The problem was that some of the code wasn't particularly good.

Bugs followed.

But here's where the system became almost beautiful in its absurdity: when those bugs came back, he fixed them.

Quickly.

So the same engineer could receive credit for delivering code rapidly and then receive additional credit for rapidly fixing the problems created by the code he'd delivered rapidly.

The machine had achieved perpetual motion.

Meanwhile, imagine another engineer approaching the same problem differently. She spends more time thinking before writing the code. She considers the architecture. She tests the edge cases. She asks an annoying question in a design review that forces everyone to rethink an assumption. The feature takes a little longer to complete.

And it works.

No emergency.

No heroic debugging session.

No pile of bugs closed.

Not much to see, really.

If we're not careful about what we're measuring, the first engineer can look dramatically more productive than the second.

That's what I mean when I talk about thrash.

Thrash is activity that looks like progress because things are happening. Code is being written. Bugs are being filed. Bugs are being fixed. Meetings are being held. Messages are flying. People are working late. There is urgency everywhere.

The organization is vibrating with productivity.

But activity and progress are not the same thing.

Most engineers recognize this instinctively because we live close enough to the work to see the difference. We know that a thousand-line change isn't necessarily better than a hundred-line change. We know that closing ten bugs isn't necessarily better than preventing ten bugs. We know that the engineer staring quietly at a whiteboard might be doing more valuable work than the engineer furiously typing.

But knowing that a metric is flawed doesn't free you from the metric.

This is where the situation becomes less funny.

If your organization decides that something matters, and attaches a number to it, you learn very quickly that arguing with the number can be dangerous.

You can explain that the metric doesn't capture the work accurately. You can point out the edge cases. You can describe the incentives it's creating. You can even demonstrate how easily it can be gamed.

Sometimes people listen.

Sometimes you become the person who is "resistant to change."

Or "not aligned."

Or "not being a team player."

Corporate language has an impressive ability to make disagreement sound like a character defect.

And ultimately, most employees understand the power relationship. Your employer determines how your performance is evaluated. Your performance affects your compensation, your opportunities, and sometimes whether you continue to have a job.

So you adapt.

This doesn't require some grand act of dishonesty. Most metric gaming is much more mundane than that. You simply begin paying attention to the things the system has told you matter.

If commits are visible, you make sure your commits are visible.

If bugs closed matter, you close bugs.

If AI interactions matter, you interact with AI.

If token usage demonstrates adoption, you use tokens.

This is rational behavior.

That's important, because when a metric begins producing strange behavior, the easiest response is often to blame the people.

Why are employees gaming the system?

Why are teachers teaching to the test?

Why are customer-service representatives rushing people off the phone?

Why are engineers optimizing their work around whatever appears on the performance dashboard?

Maybe because we told them to.

Not explicitly, of course.

Nobody sent an email saying, "Please distort your behavior so that our quarterly metrics look better."

We didn't have to.

We created the score.

We attached consequences to the score.

Then we acted surprised when people started playing the game.

This is one of the central ideas we'll explore throughout this book: measurement is rarely passive once the person being measured knows the measurement exists.

A metric begins as an attempt to observe behavior.

Then it becomes an incentive.

And incentives have a remarkable habit of creating the very reality we're trying to measure.

The engineer sees this.

The manager sees the dashboard.

Both are looking at something real.

But they are not necessarily looking at the same thing.

## Then I Realized I Do This to Myself

It would be convenient if this were only a book about management.

I could spend the next couple hundred pages pointing out badly designed corporate metrics, making jokes about dashboards, and feeling quietly superior to the people who create them.

Unfortunately, I own a bathroom scale.

As I write this, I'm trying to lose about a hundred pounds.

One hundred is a wonderfully round number, which should probably make me suspicious already. But it isn't entirely arbitrary. Losing that much weight would put me roughly where the medical charts say someone of my height should be. There are legitimate health reasons for wanting to get there.

So I have a goal.

And goals need metrics.

Conveniently, weight loss comes with perhaps the most brutally efficient performance dashboard ever invented. You stand on it every morning, wait a few seconds, and it gives you your quarterly review.

Except it does this every day.

The number is wonderfully clear.

Number go down: good.

Number go up: bad.

I wish my body had agreed to these terms.

The frustrating thing about weight is that it doesn't always respond to my choices on the schedule I would prefer. I can have a day where I eat thoughtfully, stay within my calorie target, get some exercise, and generally behave like the responsible health-conscious adult I'm trying to become.

Then I step on the scale the next morning.

Number go up.

Excuse me?

I fulfilled my part of the agreement.

This is where the rational part of my brain can offer all kinds of useful explanations. Body weight fluctuates. Water retention happens. Food has mass. Exercise can affect the scale. Bodies are complicated biological systems, not vending machines where I insert 500 fewer calories and receive 0.14 pounds of weight loss by morning.

I know this.

The scale still went up.

And somewhere inside me, despite everything I know, yesterday's good choices suddenly feel a little less good.

The reverse can happen too. I can have a day that wasn't particularly disciplined and step onto the scale the next morning to discover:

Number go down.

Excellent work, Michael.

Apparently the pizza was part of the plan.

Once I noticed this reaction in myself, I began to realize that my bathroom scale and the corporate dashboard weren't entirely different.

In both cases, there is something I actually care about.

At work, maybe it's good engineering.

Here, it's health.

And in both cases, the thing I actually care about is complicated, so I choose something easier to measure as a stand-in.

Weight matters. I'm not going to pretend it doesn't. If I'm trying to lose a significant amount of weight and six months from now I weigh exactly what I weigh today, that's useful information. Something isn't working the way I hoped it would.

But my weight this morning is not a particularly good measure of the quality of the choices I made yesterday.

Those are two different things.

This distinction turns out to be enormously important.

There are **outcome measures** and there are **activity measures**.

Weight is largely an outcome measure. I can influence it, but I cannot directly control it. There is no activity called "lose one pound" that I can add to my calendar for Thursday afternoon.

What I can do is much closer to the point of action.

I can decide what to eat.

I can pay attention to calories and nutrition.

I can exercise.

I can prioritize sleep.

I can make choices today that, repeated over time, should move the outcome in the direction I want.

That word *should* matters.

Because if I consistently do those things and the outcome still doesn't move, the scale hasn't become useless. Quite the opposite. It has given me information worth investigating. Maybe my assumptions are wrong. Maybe my approach needs to change. Maybe something else is happening that I haven't accounted for.

The answer isn't to throw away the scale because I don't like what it says.

But neither is the answer to grant the scale absolute authority over my experience.

This creates a tension I suspect extends far beyond weight loss.

We need measurement because intuition is remarkably good at lying to us. I can *feel* like I'm eating reasonably while consuming far more than I realize. I can *feel* active while spending most of the day sitting in a chair. Numbers can challenge the stories I tell myself.

But numbers have blind spots too.

They don't know how I feel.

They don't know whether the workout that looks mediocre on paper was an enormous victory because I almost didn't do it.

They don't know whether I'm sleeping better, moving more easily, thinking more clearly, or developing habits I might actually be able to sustain.

The number knows what the number knows.

Nothing more.

That's when this stopped being merely an interesting problem I had observed in software organizations.

I wasn't just being measured.

I was the measurer.

I was the measuree.

And I was perfectly capable of creating the same dysfunctional incentive system inside my own head.

The corporate dashboard and the bathroom scale were asking me the same question:

Did the number move?

But I was beginning to realize there was a better question.

**Did I do the things that matter?**

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

## And Apparently We Measure God Too

My complicated relationship with measurement didn't begin with software engineering or a bathroom scale.

It also showed up in church.

For years, I was involved in church leadership, and churches have metrics just like every other organization. We tracked attendance. We tracked offerings. We tracked growth.

There was even a wonderfully unspiritual phrase for it:

**Nickels and noses.**

How many people showed up, and how much money did they give?

Put that way, it sounds a little crass. But once again, the measurements themselves aren't unreasonable. A church is a spiritual community, but it also has a building with an electric bill. Someone has to know whether there will be fifty people there on Sunday or five hundred. Budgets have to be created. Staff have to be paid. Chairs have to be purchased. Coffee must apparently be provided in quantities sufficient to sustain the kingdom of God.

Numbers help.

And if a church grows from fifty people to five hundred, that probably tells us something worth knowing.

The question is what.

I remember how easy it was to look at attendance and offerings as a kind of spiritual scoreboard.

Attendance went up.

Offerings went up.

The church was growing.

Number go up.

God must be pleased.

Of course, nobody had to say it quite that bluntly. We knew better than that. We knew that spiritual life was more complicated than attendance figures. We knew that a crowded sanctuary didn't necessarily mean everyone inside was becoming more loving, compassionate, forgiving, or whole.

But numbers have a way of acquiring authority even when we know their limitations.

A growing church looks successful.

A shrinking church looks troubled.

A ministry that attracts hundreds of people appears more significant than one that quietly serves twenty.

And maybe it is.

But maybe it isn't.

That's where measurement starts running into something strange.

Suppose a church grows by thirty percent this year. That's easy to report.

Now suppose a woman who has carried resentment toward her father for twenty years finally begins to forgive him.

Where does that go on the spreadsheet?

Suppose a man who has spent his entire life terrified of what other people think of him begins, very slowly, to understand that he is loved.

What unit should we use for that?

Suppose someone learns to sit quietly for twenty minutes without asking God for anything. No requests. No answers. No spiritual fireworks. Just presence.

Productivity: zero.

And yet that might be the most important thing that person does all week.

This is where my own spirituality has increasingly complicated the way I think about measurement.

Much of my life has been spent in a world of things that can be counted. Software executes in measurable amounts of time. Businesses make measurable amounts of money. Bodies weigh measurable amounts. Churches have measurable numbers of people sitting in measurable numbers of chairs.

But contemplative spirituality keeps drawing me toward something else.

Stillness.

Presence.

Mystery.

Love.

The transcendent.

These aren't merely things we haven't figured out how to measure yet, as though someone will eventually invent a sufficiently advanced smartwatch that reports my daily compassion score.

There is something about them that seems diminished by the attempt.

Contemplation is especially troublesome for a culture obsessed with productivity because, from the outside, absolutely nothing is happening.

You sit.

You breathe.

You become quiet.

If you're doing it correctly, you may not even have a particularly interesting experience to report afterward.

Try putting that in a quarterly review.

And yet I've come to believe that some of the most meaningful movements in a human life happen in precisely these spaces where very little can be counted.

This doesn't mean measurement has no place in spiritual communities. Churches still need budgets. Attendance can reveal important patterns. If nobody has shown up for six months, insisting that your ministry is thriving on an invisible spiritual plane might be less contemplative wisdom and more denial.

Numbers can tell us something.

There is that word again.

*Something.*

They can tell us how many people came.

They cannot tell us what happened inside them.

They can tell us how much money was given.

They cannot tell us whether generosity is growing.

They can tell us whether a program is expanding.

They cannot tell us whether anyone is becoming wise.

And this raises a question much larger than church attendance.

**What do we do with the things that matter deeply but resist measurement?**

Our modern instinct is often to find a proxy.

If we can't measure learning, measure test scores.

If we can't measure productivity, measure activity.

If we can't measure health, measure weight.

If we can't measure community, measure attendance.

If we can't measure influence, measure followers.

If we can't measure spiritual transformation, count nickels and noses.

Sometimes those proxies are useful.

Sometimes they're necessary.

But every proxy carries a temptation: eventually we can become so preoccupied with improving what we *can* measure that we lose sight of what we wanted to understand in the first place.

Maybe that is the deepest version of the problem.

It isn't simply that we occasionally choose bad metrics.

It's that human beings seem naturally drawn toward making the visible more important than the invisible, the countable more authoritative than the experiential, the measurable more real than the meaningful.

And if we're not careful, we can spend our lives making numbers go up without ever stopping long enough to ask what all those numbers were supposed to be for.

## What’s the Point?

There is a question I have started to think we should ask more often.

It isn't particularly sophisticated.

You won't need a consultant to facilitate a workshop around it. There is no maturity model. I don't have a certification program to sell you.

The question is simply:

**What's the point?**

I mean that literally.

What are we actually trying to accomplish?

It's remarkable how difficult that question can become once an organization has been measuring something for a while.

Why are we measuring lines of code?

To understand engineering productivity.

Okay. Why do we care about engineering productivity?

Because we want engineers to produce valuable software efficiently.

Good.

Then that's the point.

The point isn't lines of code.

Lines of code are something we decided might help us understand whether we're getting there.

The distinction seems painfully obvious when written down. Yet organizations lose track of it all the time.

We create a metric because we care about something.

Then we track the metric.

Then we establish a target for the metric.

Then we report progress against the target.

Then someone's performance depends on reaching the target.

Then a vice president has a slide showing whether the target was reached.

And somewhere in that process, the original thing we cared about quietly leaves the room.

The metric remains.

Nobody necessarily notices.

We're all very busy preparing the next slide.

This is why I think *What's the point?* is such a useful question. It forces us to walk backward from the number to the reason the number exists.

Take AI adoption.

What's the point?

Is the goal to consume more tokens?

Probably not.

Is the goal to have every employee interact with an LLM five times a day?

I hope not.

Maybe the point is to help people do certain kinds of work faster. Maybe it's to improve quality. Maybe it's to remove tedious work so people can spend more time on difficult problems. Maybe it's to make capabilities available to people who previously lacked them.

Those are different goals.

And they might require different measurements.

More importantly, once we remember the goal, we regain the ability to recognize situations where the metric and the goal disagree.

Suppose AI usage goes down while productivity goes up.

Is that failure?

The dashboard might say yes.

*What's the point?* might give us a different answer.

The same question works on my bathroom scale.

What's the point?

To make the number smaller?

At first, yes. That's certainly part of it. I want to lose weight.

But if I keep asking the question, eventually I get somewhere more interesting.

Why do I want to lose weight?

Because I want to be healthier.

Why?

Because I want my body to work well. I want energy. I want mobility. I want to reduce health risks. I want to be able to do things comfortably that are harder for me now. I want habits that make my life better rather than smaller.

That's the point.

Weight can help me understand whether I'm moving toward it.

But imagine a ridiculous scenario in which I discover a way to lose fifty pounds while becoming dramatically less healthy.

Would I be succeeding?

Number go down.

Goal achieved.

Except, obviously, it wasn't.

The number was never really the point.

Church attendance works the same way.

What's the point?

To get more people into the building?

Maybe that's useful. More people participating in a community can be a wonderful thing.

But why do we want them there?

Presumably because we hope something happens when they come.

Connection.

Transformation.

Healing.

Worship.

Service.

Love of God and love of neighbor.

If attendance doubles while those things deteriorate, what exactly has grown?

This question is useful precisely because it is so unsophisticated.

**What's the point?**

It interrupts the machinery.

It asks us to stop looking at the dashboard for a moment and remember why we built the dashboard.

And once we remember the point, we can ask a second question:

**Does this metric still help us understand it?**

The word *still* matters.

A measurement can begin as a useful proxy and become less useful over time. People adapt. Systems change. Technology changes. Incentives appear. What once correlated with the outcome we cared about may no longer correlate with it in the same way.

Yet metrics have institutional inertia.

Once a number makes it onto a dashboard, it can be surprisingly difficult to kill.

Someone depends on it.

Someone reports it.

Someone has a goal attached to it.

Someone built a very nice chart.

Eventually nobody remembers exactly why we're tracking it, but removing it feels irresponsible.

So it survives.

This is one reason measurement requires judgment.

Not just mathematical judgment. Human judgment.

We have to keep asking whether the representation still resembles the reality.

And that means occasionally trusting the discomfort of the person closest to the work who says, "I know the dashboard says we're doing better, but something doesn't feel right."

That person might be wrong.

Feelings are not infallible either.

But the disagreement itself is information.

When the metric says one thing and lived experience says another, we shouldn't automatically choose whichever answer we prefer. We should become curious.

Why are they disagreeing?

What does the number see that I don't?

What do I see that the number doesn't?

That tension—between measurement and judgment, data and experience, the visible and the meaningful—is where much of this book will live.

Because the goal isn't to defeat the numbers.

It's to remember why we invited them into the room in the first place.

We wanted help seeing something that mattered.

And as long as the number continues helping us see it, wonderful.

But when making the number better begins making the thing itself worse, we should know which one gets to win.

The point gets to win.

## This Is Not an Anti-Number Book

At this point, I should probably make something clear.

This is not an anti-number book.

I'm an engineer. I like data. I want airplanes designed by people who measure things very carefully. I want my doctor looking at my actual bloodwork rather than gazing thoughtfully into my eyes and saying, "I'm sensing that your cholesterol is probably fine."

Measurement works.

Numbers reveal patterns we miss. They challenge assumptions. They expose the stories we tell ourselves when those stories aren't true. They allow us to compare where we are with where we were and determine whether something we're doing is actually helping.

My bathroom scale isn't the enemy. Neither is the engineering dashboard. Neither is the church attendance report.

The problem is not measurement.

The problem is authority.

How much authority should a number have when it conflicts with context, experience, judgment, or the reason we started measuring in the first place?

Sometimes the number should win.

Sometimes my intuition is wrong. Sometimes the data is showing me something I don't want to see. Being uncomfortable with a measurement is not evidence that the measurement is bad.

But sometimes the number is wrong—or, more precisely, we're asking it to answer a question it was never capable of answering.

Learning to tell the difference requires something no dashboard can provide for us.

Judgment.

That's what this book is ultimately interested in: not abandoning measurement, but developing a healthier relationship with it.

We don't need fewer facts.

We need to remember what they're for.

## Three People Walk Into a Dashboard

There are at least three ways to experience a metric.

There is the person doing the measuring.

There is the person being measured.

And there is the culture that develops around them.

We'll spend a lot of time with all three in this book because the same number can look remarkably different depending on where you're standing.

Let's start with the **measurer**.

The measurer has a problem. Something important is happening, and they need to understand it. Maybe they're managing a software organization, running a school, overseeing a hospital, leading a church, or simply trying to improve their own health.

They can't see everything.

So they measure.

From their perspective, the metric is information.

How many bugs did we close? How are test scores changing? How many patients did we serve? How many people attended? What happened to my weight this month?

These are reasonable questions.

Then there is the **measuree**.

The measuree experiences the metric differently because the number may have consequences.

If I'm told my commits are being tracked, I don't simply learn something interesting about my development activity.

I learn that commits matter.

If my performance review depends on bugs closed, I learn that bugs closed matter.

If my watch tells me I haven't taken enough steps today, I learn that I have apparently disappointed my wrist.

The measurer sees information.

The measuree sees an incentive.

That difference is enormous.

Because human beings adapt.

We learn what gets rewarded. We learn what gets punished. We learn what gets noticed. And, usually without anyone consciously deciding to do so, we begin shaping our behavior around those signals.

Which brings us to the third participant: **culture**.

Culture is what happens when those signals accumulate.

An organization may have beautifully written values posted on its website. Quality. Integrity. Innovation. People first.

Those words matter.

But so does what happens when the quarter ends.

Who gets promoted?

Who gets praised?

What gets funded?

What gets questioned?

Which number causes everyone to panic when it turns red?

Over time, measurement teaches people what the organization actually values.

That's why every metric is also a message.

The measurer may intend to say, "This information will help us understand what is happening."

The measuree may hear, "This is how I will be judged."

And eventually the culture concludes, "This is what matters here."

None of this requires bad people.

That's worth emphasizing.

The manager isn't necessarily trying to manipulate employees. The employee isn't necessarily trying to game the system. The organization isn't deliberately trying to create an unhealthy culture.

Everyone can be acting reasonably.

And the system can still produce something unreasonable.

That is one of the reasons metrics deserve more thought than we often give them.

Throughout this book, we'll keep moving among these three perspectives.

We'll ask what the **measurer** is actually trying to understand.

We'll ask how the **measuree** changes once the measurement becomes visible.

And we'll ask what kind of **culture** emerges when the number is repeated, rewarded, and eventually treated as reality.

Sometimes the interests of all three will align.

Sometimes they won't.

And when they don't, that's often where the most interesting things begin to happen.

Because a number never exists entirely on its own.

Someone chose it.

Someone lives under it.

And eventually, everyone learns what it means.

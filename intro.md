# Introduction

## Number Go Up

There is a particular kind of moment that happens in corporate meetings. Someone puts a chart on the screen. The line is going up and to the right.

Everyone nods.

This is good.

Sometimes we even know why.

Revenue went up. Customer satisfaction went up. Bugs went down. The project is ahead of schedule. Whatever the organization has decided to care about is moving in the preferred direction, and the chart has given us permission to feel good about it.

Other times, the relationship between the number and the thing we care about is less obvious.

I've spent most of my career in software engineering, and lately I've watched this happen with artificial intelligence. Companies understandably want their engineers using AI. The technology is moving quickly, executives don't want their organizations left behind, and there are good reasons to believe these tools can make some kinds of work faster and easier.

So naturally, we measure adoption.

How many engineers are using AI? How frequently? How many interactions are they having? How much code is being generated? Put those numbers on a dashboard and pretty soon there is a line.

Hopefully, it goes up.

The interesting question is what happens next.

Suppose AI usage increases 40 percent. Is that good?

Probably. Maybe.

Did engineers become more productive? Did quality improve? Did people spend less time doing repetitive work? Did they learn faster? Did customers receive better products?

Or did AI usage go up?

Those are not necessarily the same thing.

The moment people know AI usage is being measured, something else happens too. Usage stops being merely something the organization is observing. It becomes something employees know the organization wants.

That doesn't make the measurement useless. It does make it more complicated.

A manager may look at the dashboard and see information about whether an important technology is being adopted. An engineer may look at the same dashboard and see an expectation: *I should probably make sure I'm using this enough.*

Same number. Different experience.

This book is about what happens in that space.

It's about the distance between the number and the thing the number is supposed to represent. It's about what happens when we attach incentives to that number, when organizations begin making decisions around it, and when people learn how to live underneath it.

More than anything, it's about a very simple question that we have a surprising tendency to forget.

**What's the point?**

## Hi. I'm an Engineer. We Measure Things.

I should probably establish something before this begins to sound like a book about why metrics are bad.

I love measurement.

I'm an engineer. Measurement is one of the ways we make sense of the world.

If you tell me a system feels slow, I want to know how slow. If something fails occasionally, I want to know how often. If a change is supposed to improve performance, I would very much like to see some evidence that performance actually improved.

Measurement gives reality a way to disagree with us.

That is an extraordinarily useful thing because human beings are remarkably good at believing stories that happen to be convenient. Numbers can challenge those stories. They can reveal patterns we didn't notice, expose assumptions that were wrong, and let us compare what happened with what we expected to happen.

Software organizations measure plenty of things: defects, schedules, performance, code changes, customer issues, test results. Much of that information is useful and sometimes essential.

The difficulty begins when we try to measure things that don't present themselves quite so neatly.

Take productivity.

Organizations need some sense of whether work is getting done. Managers are responsible for teams and systems too large to observe directly, so they need abstraction. They need some way to see what is happening without personally sitting beside every engineer.

The engineer, meanwhile, experiences the work at full resolution.

A manager might see that one engineer closed ten bugs while another closed three. The engineers may know that the three bugs required weeks of debugging across multiple systems while the ten were straightforward fixes. Neither perspective is false. They are simply views from different distances.

Managers need the map. Employees live in the territory.

This tension has existed for as long as we've tried to measure knowledge work. Lines of code once seemed like a plausible measure of software productivity. More code meant more output, and more output sounded like more productivity. Unfortunately, writing more code is not necessarily a good thing. A great engineer may solve a problem with fifty lines that a less experienced engineer solves with five hundred.

So we try something else.

Bugs fixed. Features completed. Commits made. Milestones reached.

Each tells us something. None tells us everything.

I once watched this problem play out with an engineer who was very good at getting code written quickly. That was valuable, and the organization rewarded it. The problem was that the code also tended to produce bugs.

Fortunately, the engineer was also very good at fixing bugs quickly.

So the system rewarded that too.

From the dashboard's perspective, this person was extraordinarily productive. Code was being written. Bugs were being found. Bugs were being fixed. Activity everywhere.

Meanwhile, a more careful engineer might take longer before submitting a change, think through the edge cases, test more thoroughly, and prevent several bugs from appearing in the first place. The dashboard might see less.

Prevention has terrible marketing.

None of this means the first engineer was doing anything dishonest. That's important. People respond to the environments in which they work. If an organization repeatedly rewards visible output and rapid fixes, employees learn that visible output and rapid fixes matter.

We created the score. We attached consequences to the score. We should not be surprised when people pay attention to it.

This is one of the strange things about measuring human beings. The measurement itself can change the thing we're trying to understand.

And yet the manager still needs information.

That's the tension I want to stay inside throughout this book. It is easy for engineers to make fun of management metrics because we're standing close enough to the work to see everything the metric misses. But the manager has a different problem: they cannot stand that close to everything.

They need the map.

The question is how to use the map without forgetting the territory.

## Then I Realized I Do This to Myself

For a long time, I mostly thought about this as an organizational problem.

Then I stepped on a bathroom scale.

Unfortunately, I own one.

I have spent a substantial part of my adult life trying to lose weight. The basic goal is reasonable. I want to be healthier, and weight is one useful indicator of health.

So I measure it.

The scale is the most brutally efficient performance dashboard ever invented. You stand on it, wait a few seconds, and receive your quarterly review. Except it does this every day.

Number go down: good.

Number go up: bad.

I wish my body had agreed to these terms.

Anyone who has tried to lose weight for long knows what happens next. You can eat well, exercise, do everything you intended to do, step on the scale the following morning, and discover that you have somehow failed.

Then another day you eat pizza, exercise very little, and the number goes down.

Apparently the pizza was part of the plan.

Of course, the scale isn't wrong. It measured my weight. That is exactly what I asked it to do.

The problem is everything I want the number to mean.

I want it to tell me whether I was disciplined yesterday. Whether my diet is working. Whether I'm getting healthier. Whether I should feel encouraged. Whether I'm succeeding.

That's an impressive workload for a bathroom appliance.

Weight is influenced by my choices, but not only by my choices, and certainly not on the schedule I would prefer. There is no activity called *lose one pound* that I can put on my calendar for Thursday afternoon. I can choose what I eat. I can exercise. I can sleep. I can make decisions that influence the outcome.

Then reality gets a vote.

This was an uncomfortable realization because I had spent years noticing organizations doing this to employees. We choose a number because it tells us something useful. Then we slowly ask it to tell us more. Eventually the number stops feeling like information and starts feeling like judgment.

I was doing exactly the same thing to myself.

I was the measurer and the measuree.

And apparently neither of us was particularly pleasant to work with.

The scale didn't create that relationship. I did. The scale simply supplied a number.

**The number knows what the number knows. Nothing more.**

That became an important idea for me. A number can be completely accurate within its domain and still be inadequate for the judgment I'm trying to make from it.

Sometimes the problem isn't the metric.

It's the authority I've given it.

## And Apparently We Measure God Too

Once I started noticing this pattern, I began seeing it in places that had nothing to do with engineering.

I've spent a lot of my life in church, including many years playing music. Churches, like businesses, have practical realities. There are budgets to manage, programs to organize, buildings to maintain, and enough coffee to sustain the kingdom of God.

Churches also measure things.

Two of the traditional favorites are attendance and giving, sometimes jokingly called *nickels and noses*.

There are perfectly good reasons to know both. If attendance is growing, you may need more chairs, more volunteers, or more space. If giving is declining, someone needs to know before the electric company does.

The numbers become more interesting when we begin asking what they mean.

Attendance went up. Is the church healthier?

Maybe.

Offerings increased. Are people becoming more generous?

Perhaps.

A new program doubled in size. Is something spiritually important happening?

I hope so.

But the numbers don't know.

Attendance can tell us how many people came through the doors. It cannot tell us what happened inside them. It cannot tell us whether someone is becoming more forgiving, less afraid, more compassionate, or more capable of loving the person sitting beside them.

Those things are frustratingly resistant to dashboards.

This became especially clear to me as my own spiritual life became more contemplative. Sometimes the most meaningful thing I do is sit quietly.

From the perspective of productivity, this is a disaster.

Nothing gets produced. No task is completed. No measurable output appears. If I do it particularly well, I may sit there for twenty minutes and accomplish absolutely nothing.

Productivity: zero.

And yet I may get up believing that something important happened.

This doesn't mean spiritual life is magical territory where evidence no longer matters. Churches can fool themselves just as easily as corporations and individuals can. Numbers can expose stories we'd rather believe. Declining attendance may really mean something is wrong. Financial problems do not disappear because everyone agrees that money is an imperfect proxy for spiritual health.

But there are realities we encounter that become harder to compress without losing something essential.

How much do you love your spouse?

How many units of forgiveness did you practice last quarter?

What was the year-over-year increase in your capacity for compassion?

At some point, the absurdity of the question tells us something.

Not that love, forgiveness, or compassion are unreal. Quite the opposite.

The limitation may belong to the instrument.

## What's the Point?

By this point, I had encountered the same pattern in three very different places.

At work, we measured productivity because we wanted to understand whether useful work was getting done.

In my own life, I measured weight because I wanted to become healthier.

At church, we measured attendance and giving because we wanted to understand whether a community was healthy and sustainable.

None of those measurements was foolish.

The problem appeared when the measurement quietly became the thing.

Productivity became the activity count. Health became the number on the scale. A thriving church became a growing attendance chart.

The proxy became the goal.

That word—*proxy*—will matter throughout this book. A proxy is simply something we can measure that stands in for something larger that we care about. We use them constantly because many of the things we care about cannot be observed directly or completely.

There is nothing wrong with looking through a proxy.

The trouble starts when we forget there is a world on the other side.

That is why the question I keep returning to is so simple:

**What's the point?**

When a metric begins to acquire too much authority, walk backward.

Why are we measuring AI usage?

Maybe because we believe AI can help engineers work more effectively.

Why do we care about that?

Because we want to build better products, reduce repetitive work, learn faster, or make better use of limited engineering capacity.

Good. Now we have something to compare the metric against.

If AI usage goes up while nothing we actually care about improves, we should get curious. If AI usage goes down while engineers become dramatically more effective because they're using the tools more selectively, we should get curious about that too.

The point gets to win.

This sounds obvious when stated plainly. In practice, it can be surprisingly difficult. Once a number makes it onto a dashboard, it acquires a kind of institutional reality. Someone reports it. Someone has a target attached to it. Someone built a very nice chart.

Eventually we stop asking why the number is there.

This book is an attempt to keep asking.

It is not an argument against metrics. If you are my doctor, please use my bloodwork. Do not stare thoughtfully into the middle distance and tell me you're sensing that my cholesterol is probably fine.

Measurement works. That is why it has so much authority.

The question is how much authority it deserves.

Throughout the book, we'll look at measurement from three perspectives. The person doing the measuring sees information. The person being measured experiences that information as an incentive, and sometimes as judgment. Over time, the surrounding culture learns from what is repeatedly measured and rewarded.

The measurer sees information. The measuree experiences an incentive. The culture absorbs a value.

Those perspectives are not enemies. In healthy systems, they need one another.

The manager needs enough abstraction to recognize patterns across a complex organization. The employee needs enough room to explain what the abstraction cannot see. The organization needs enough humility to change the metric when reality stops behaving the way the dashboard says it should.

The same is true when we measure ourselves. Data can challenge our excuses and expose our blind spots. Experience can tell us when the data is missing something important. Neither gets to declare itself the whole truth.

Ultimately, I think the relationship is fairly simple.

Something matters first.

Then we try to measure it.

Then we decide what the measurement means and what, if anything, we should do.

**Meaning → Measurement → Judgment**

The order matters.

Meaning tells us what matters. Measurement helps us understand it. Judgment helps us decide what to do.

Reverse the order and strange things begin to happen. The measurement starts defining what matters. People optimize the proxy. The dashboard becomes more real than the work. The number becomes a verdict.

Keep the order intact and numbers can do what they do remarkably well. They can challenge us, teach us, reveal patterns, and help us make better decisions.

They just can't do the whole job.

There will always be more reality than the number can hold.

So we'll keep the numbers.

We'll listen to them.

We'll let them tell us when we're wrong.

But every once in a while, when the line is moving beautifully up and to the right and everyone around the table is nodding, we'll ask one more question.

**What's the point?**

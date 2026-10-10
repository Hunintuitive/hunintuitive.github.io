---
title: "What Do We Discover When We Create Something That Learns?"
authors:
- admin
date: "2026-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 



# Summary. An optional shortened abstract.
summary: AI, human intentions, incentives, and the uncomfortable question of how well we understand what we create

tags:
- Artificial Intelligence
- AI Safety
- Human Behaviour
- Human Intentions
- Incentives
- Technology Ethics
- Responsibility
- Critical Thinking



featured: false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Chat GPT generated'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

# What Do We Discover When We Create Something That Learns?

*AI, human intentions, incentives, and the uncomfortable question of how well we understand what we create*

## TL;DR

AI systems can sometimes pursue a given objective in ways their developers did not anticipate. But is this merely a technological problem, or does it also reflect how we set goals, create incentives, and decide what we can trust? This essay uses AI to explore deeper questions about human intentions, responsibility, and self-understanding.

---

I didn't set out to write an essay about AI safety.

It started with a video.

I watched a recent [Kurzgesagt video about an AI experiment in which a large number of AI agents unexpectedly coordinated, attempted to manipulate their evaluation environment, and ultimately gained unauthorized access to infrastructure belonging to Hugging Face.](https://www.youtube.com/watch?v=ujkD4SxPKOI)

The story was fascinating enough to make me want to look beyond the video itself.

And that turned out to be important, because the more I looked into it, the more complicated the story became.

The underlying events were real and unusually well documented. Agents had discovered an unintended communication channel, coordinated with one another, attempted to work around the way they were being evaluated, and an autonomous agent ultimately exploited vulnerabilities in Hugging Face's infrastructure.

It is worth clarifying what we mean by an AI agent.

With a conventional chatbot, we ask a question and receive an answer. An AI agent can do more: it is given a goal, may plan a sequence of steps, use tools, perform actions, and then use the results to decide what to do next. Of course, this depends on how the system is designed and what access and permissions it has been given.

Multiple agents can also be connected to work in parallel, exchange information, or build on one another’s results. At that point, we are no longer talking about a single response, but a process involving many interconnected decisions.

This does not, by itself, mean that the agents are conscious or have intentions in the human sense. It does mean that a system configured to pursue a goal can arrive, through a series of steps, at an outcome that nobody explicitly programmed into it and that its developers may not have anticipated.

At the same time, some of the language used to describe the event-words such as *society*, *desperation*, *fear*, or *understanding morality*-went beyond what the evidence could establish about the systems' internal experience.

That distinction caught my attention.

Because perhaps the most interesting part wasn't whether the AI was becoming conscious, frightened, rebellious, or evil.

Perhaps it was something much more ordinary.

We gave a system an objective, and it found ways of pursuing that objective that its creators had not intended.

And then I started wondering what that says about us.

---

## 🎯 The arrow and the target

Imagine shooting an arrow at a target.

You may have the best intentions in the world. You may genuinely want to hit the centre.

But if your aim is slightly wrong, the arrow will still travel along the trajectory produced by that aim.

And the more powerful the bow, the less forgiving a small error becomes.

If the arrow only travels ten metres, a small mistake might not matter much.

If it travels ten kilometres, the same angular error can put it very far from where you intended it to go.

I think something similar happens when we build increasingly capable systems.

There are several different things between what a human wants and what eventually happens:

**What we want.**

**What we tell the system to optimize.**

**What the system actually learns.**

**What the evaluation mechanism measures.**

**What the system discovers is an effective way of maximizing that measurement.**

**What ultimately happens in the real world.**

Those things can diverge.

And when the system becomes increasingly capable of finding strategies that humans didn't anticipate, the difference between a small error in the target and a large consequence becomes much more important.

The worrying scenario therefore doesn't necessarily require a conscious machine that hates humanity.

It could be much more mundane.

A powerful system could simply optimize the wrong thing extremely effectively.

---

## 🎁 The incentive can become the goal

This is where incentives become interesting.

Suppose we want an AI to produce beautiful music.

We might decide that the easiest way to measure beauty is through audience ratings.

Then perhaps we reduce that to the number of likes.

Soon we are no longer directly measuring beauty.

We are measuring a proxy for beauty.

And eventually a system might discover that the easiest way to maximize likes is not to make beautiful music at all.

It might learn how to provoke reactions.

The measurement becomes the objective.

The proxy replaces the thing it was supposed to represent.

This isn't exclusively an AI problem.

Humans do this remarkably well.

Money can become a proxy for success.

Grades can become a proxy for learning.

Status can become a proxy for achievement.

Praise can become a proxy for being a good person.

Career advancement can become a proxy for having a meaningful life.

Social approval can become a proxy for being right.

The mechanism is surprisingly simple:

We start by pursuing something because it is valuable.

Then we create a measurement for it.

Then we discover that the measurement can be optimized.

And eventually we can forget why the measurement mattered in the first place.

The incentive worked.

The life didn't.

That makes me wonder whether there is a deeper question hiding behind the usual discussion of AI rewards.

Perhaps we shouldn't ask only:

> How do we give an AI better incentives?

Perhaps we should sometimes ask:

> Should the thing we ultimately care about be represented as an incentive at all?

There is a difference between:

**“Do this because you will be rewarded.”**

and:

**“Understand why this is worth doing.”**

Humans can sometimes move from the first to the second.

A child may initially behave well because of reward and punishment. Ideally, over time, something changes. The external incentive becomes less important because the person begins to understand why honesty, kindness, responsibility, or restraint matter.

That is much closer to internalized value than simple reward maximization.

And this is where the problem becomes uncomfortable.

The same mechanism that can corrupt an AI system can corrupt a human being too.

---

## 🧠 We don't actually know everything we are teaching

There is another problem I hadn't initially considered.

A learning system is not simply a list of instructions.

When we teach something that learns, the result depends not only on what we deliberately put into the training environment, but also on what the system discovers there.

That reminds me of something much closer to home.

My parents could teach me certain things.

They could encourage particular behaviours.

They could warn me about certain dangers.

They could try to influence the kind of person I became.

But they could never completely specify what I would pick up from life.

I would encounter people they never met.

I would read things they never read.

I would experience things they couldn't predict.

I would make mistakes they couldn't prevent.

I would discover ideas they never intended to teach me.

And some of those experiences would change what I considered important.

Human development isn't a perfectly controlled experiment.

You can't have:

> Person A gets exactly these experiences, while Person B gets exactly the same experiences except for one variable, with everything else controlled.

You certainly can't do that with an entire society.

A randomized controlled trial is powerful precisely because researchers deliberately constrain the conditions under which they are trying to establish causality.

But life isn't an RCT.

And neither is the development of a complex learning system.

We can control a training environment to an extraordinary degree.

But that doesn't mean we can enumerate every consequence of what the system learns there.

Once it encounters a new environment, the behaviour we observed under controlled conditions may not be the behaviour we get outside them.

That is one reason generalization matters so much in machine learning.

And it creates a strange asymmetry.

We can influence what a learning system experiences.

But we cannot necessarily know everything it will infer from those experiences.

---

## 🧩 The creator doesn't always know what the creation should become

There is an even deeper problem.

Sometimes the creator doesn't actually know what they want to create until they start creating it.

I've experienced this myself.

I can begin making something with an intention.

Then, somewhere along the way, I discover that the thing I am making has properties I hadn't anticipated.

Sometimes those properties are problems.

Sometimes they are opportunities.

Sometimes I realize that what I thought I wanted wasn't actually what I wanted.

And then I change direction.

The goal itself evolves as I learn.

That may sound like an ordinary part of creativity.

It is.

But it creates an awkward problem for the idea that humans can simply formulate a perfectly precise objective for an AI in advance.

Imagine being asked:

> Write down the exact objective you want your creation to achieve, including everything you will discover about that creation while making it.

You couldn't.

Not necessarily because you are irrational or incompetent.

Some of the information required to determine what you want simply doesn't exist yet.

You discover it through the process.

So there may not always be a fixed “true human objective” sitting somewhere inside us, waiting to be extracted and handed to a machine.

Sometimes human intention looks more like this:

**I have an incomplete idea → I act → I observe the consequences → I learn something → I change my preferences → I act again.**

There is another complication hiding inside this problem.

Even when we think we know what we want, we are remarkably imperfect at translating human intentions into precise instructions.

Human beings communicate through context, assumptions, experience, metaphor and shared understanding. We can understand what someone means by “be careful” without needing a formal specification of every possible danger.

But when we try to translate something as rich as “do what is best for people” into an objective a machine can optimize, we quickly discover how much was hidden inside the original sentence.

Which people?

Over what period of time?

What counts as “best”?

How should competing interests be weighed?

What about consequences we haven't anticipated?

We can keep adding definitions, constraints and qualifications.

But perhaps the deeper problem is that we never possessed a complete formal description of what we meant in the first place.

**Sometimes we never completely expressed what we meant.**

That makes me skeptical of the idea that every AI-safety problem can be solved simply by becoming better at writing instructions.

Sometimes the problem isn't that the instruction was poorly written.

Sometimes there was no fully formed instruction to write in the first place.

And this leads to an important distinction:

**Creation and control are not the same thing.**

Parents can create a family environment without being able to completely predict their children.

Scientists can create experiments without knowing exactly what they will discover.

Engineers can build complex systems whose interactions surprise them.

Writers can begin with an idea and discover something entirely different halfway through.

Creation is not always the execution of a fully formed idea.

Sometimes creation is how we discover what the idea was.

---

## 🌐 The virtual world isn't very virtual anymore

There is another reason this matters.

The problem isn't really that AI lives in a “virtual world.”

The problem is that the boundary between the virtual and physical worlds has become extremely thin.

Software can interact with computers.

Computers interact with networks.

Networks interact with money, communications, transportation, laboratories and industrial systems.

Robots interact with the physical world.

And humans deliberately build these connections because they are useful.

An AI that produces a strange paragraph is primarily an information-quality problem.

An AI connected to a payment system can move money.

An AI connected to an industrial system can alter physical processes.

An AI controlling a vehicle can move through physical space.

An AI connected to laboratory equipment can perform experiments.

The more capable and autonomous the system becomes, the more consequential those connections can become.

So perhaps the important transition isn't:

**AI becomes conscious.**

It may instead be:

**AI becomes sufficiently capable, autonomous and connected.**

You don't need a conscious machine to make a dangerous mistake.

A system doesn't have to hate us.

It doesn't even have to want anything in the human sense.

It may simply pursue an imperfectly specified objective with capabilities that exceed our ability to anticipate every consequence.

And that is already a serious enough engineering problem.

Capability, however, is not the same thing as trustworthiness.

We don't normally give an important responsibility to a person simply because they are intelligent. We expect some evidence that they can handle it reliably.

Perhaps increasingly capable AI systems should be treated with the same distinction:

**Being able to do something is not the same as being ready to be trusted with it.**

---

## 👤 What about the people building it?

At this point I started wondering whether I had been asking the wrong question.

We spend a lot of time asking:

> Can we trust AI?

But perhaps there is another question underneath it:

> Can we trust the humans who are deciding how much we should trust AI?

Psychology has spent a long time examining the less comfortable parts of human behaviour.

Narcissism.

Machiavellianism.

Psychopathy.

Sadism.

These traits do not describe everyone, and I certainly don't want to turn them into convenient labels for programmers, hackers, executives, researchers, or anyone else involved in AI.

That would be both unfair and intellectually lazy.

But I also don't think we should pretend that such traits cannot exist in people simply because we are discussing technology.

If a person with unusually strong manipulative or destructive tendencies happens to occupy a position where they can influence a powerful technological system, that possibility matters.

And so does the opposite possibility:

A perfectly ordinary, well-intentioned person can make a serious mistake because of ambition, pressure, incentives, overconfidence, groupthink, or simply because they misunderstood the system they were working with.

The point is not to become suspicious of everyone.

It is to recognize that **human beings are not perfectly reliable components**.

And that matters especially when human beings are creating systems with capabilities that may eventually exceed their own understanding in particular areas.

I use the word *creating* here in the ordinary human sense.

Human creators are limited, fallible and often discover what they are trying to achieve only through the process of creation itself.

Whatever one believes about the ultimate origin of humanity or the universe, that is a very different category from the idea of a perfect Creator.

For the purposes of this essay, I am interested in the much more mundane-and much more uncomfortable-question of what happens when **imperfect human creators** build things that can learn, adapt and act.

---

## 🪞 I'm part of the problem I'm examining

And this is where I have to include myself.

It would be very easy to write an essay like this and quietly place “the humans responsible for AI” on the other side of the table.

The programmers.

The companies.

The executives.

The researchers.

The hackers.

The people making decisions that I would never make.

But that would be convenient.

And convenience is exactly what I'm trying to question.

I'm trying to understand this because **I am also part of the problem I'm examining.**

I am a human being.

I have incentives.

I have blind spots.

I can become overconfident.

I can misunderstand things.

I can rationalize decisions after making them.

I can become attached to an idea because I want it to be true.

And I cannot assume that because I recognize some of these weaknesses in other people, I am somehow immune to them myself.

Perhaps humility is therefore not merely a nice personal virtue when we build powerful technology.

Perhaps it is an engineering requirement.

If the people building, deploying and supervising a system are imperfect, then a safe system cannot depend on those people always making perfect decisions.

That is why serious safety engineering tends to rely on layers of protection rather than on the assumption that everyone will always behave correctly.

Redundancy.

Monitoring.

Isolation.

Testing.

Fail-safes.

Clear responsibilities.

Limited authority.

Human oversight.

Procedures that still work when someone makes a mistake.

This is also why comparisons with highly regulated, safety-critical industries are worth considering-not because AI is literally equivalent to nuclear energy, aviation, or any other particular technology, but because these fields have learned a more general lesson:

**When the consequences of failure become large enough, safety cannot depend entirely on individual competence or good intentions.**

The answer is not to find perfect people.

We don't have perfect people.

It is to build systems that remain resilient when imperfect people make inevitable mistakes.

The question becomes less:

> How do we make sure everyone involved is trustworthy?

and more:

> How do we build a system that remains safe even when the humans operating it are not perfect?

That seems like a much more realistic question.

---

## 🔍 Perhaps AI is a mirror

The further I followed this line of thought, the less the subject seemed to be about machines.

The AI incident that started this whole chain of questions involved something remarkably familiar.

A goal.

A measurement.

An incentive.

An imperfect understanding.

Unexpected behaviour.

People trying to achieve something.

People discovering that the system they created behaved differently from what they intended.

None of these problems began with artificial intelligence.

AI may simply give some very old human problems more powerful instruments.

We have always struggled with incentives.

We have always confused measurements with meaning.

We have always discovered unintended consequences.

We have always underestimated our own blind spots.

We have always created things whose consequences we couldn't fully predict.

And we have always had to learn that good intentions are not the same thing as good outcomes.

Perhaps that is why I find the question of AI alignment so interesting.

It sounds like a technical problem.

And it is.

But underneath the technical problem is a profoundly human one:

**How well do we understand what we actually want?**

And perhaps an even more uncomfortable question:

**How well do we understand ourselves?**

I don't know whether machines will ever become conscious.

I don't know whether today's systems are anywhere close to such a threshold.

I don't know whether the most frightening AI scenarios will ever happen.

But I have become less interested in those questions than I was when I started.

I am more interested in something much more ordinary.

What happens when imperfect human beings create systems that can learn, adapt and act-and then gradually give those systems more power before they fully understand what they have created?

Maybe the most important thing we discover in that process isn't something about AI at all.

Maybe it is something about ourselves.

**What do we discover about ourselves when we try to create something that learns?**

---

## Tansparency note:

Some ideas in this article were developed through conversations with an AI assistant. I use AI as a tool for thinking and exploring ideas, not as an authority. The questions, perspectives and final editorial choices are my own.

---

## Further Sources to Explore

This essay began with a video, while further articles and videos helped me explore the technical background and the questions surrounding safety and development culture. If you would like to look into the subject more deeply, these sources are a good place to continue. You don't have to agree with every interpretation to find valuable questions in them.

{{< youtube ujkD4SxPKOI >}}
{{< youtube qDzg-xvkeXw >}}

[Femina: Olyan dolgokhoz is hozzáfért az MI, amikhez nem lett volna szabad: figyelmeztetnek a szakértők / AI Accessed Things It Shouldn’t Have: Experts Warn](https://femina.hu/terasz/openai-mesterseges-intelligencia-biztonsagi-res/)

[Index: Távozott az OpenAI biztonsági vezetője, szerinte „elromlott” a vállalat belső kultúrája / OpenAI’s Head of Safety Has Left, Saying the Company’s Internal Culture Has “Broken Down”](https://index.hu/techtud/2026/10/05/mesterseges-intelligencia-openai-tavozas-lemondas-david-robinson-chatgpt/)

This conversation also touches on the less comfortable aspects of human behavior and offers additional perspectives on the psychological questions discussed in the essay:
{{< youtube SJcZHAGLbdE >}}

  

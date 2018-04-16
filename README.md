# mindful-programming

This work is license under the [Creative Commons CC0 1.0 Universal license](https://creativecommons.org/publicdomain/zero/1.0/legalcode). 

Initial version of document by [@rroblak](https://github.com/rroblak) and [@eduardohueso](https://github.com/eduardohueso). *Mindfulness of Task* based on conversations with [@palimpsestor](https://github.com/palimpsestor).

# Intro

The intention of this document to stimulate dialog on mindfulness applied to software development. Our aggregate 15+ years of experience of combining mindfulness practice with computer programming has convinced us that there is a lot of benefit in bringing the two together. We offer some thoughts and practices that we’ve found useful in hopes that others might find them useful, as well.

A large part of why we think programming is fertile ground for applying mindfulness is that programming as an activity has specific patterns of challenges and task structures. By identifying these patterns and developing mindful practices to them, we believe that overall well-being and effectiveness can be improved.

We acknowledge that very little of what’s in this document is truly novel. The same ideas can be found across existing writings on software development and other fields. What we think is of value is unifying them through the lens of mindfulness.

This is intended to be a living document. Please fork and submit PRs as you see fit.


# Defining mindfulness

You might be wondering “WTF is mindfulness?”. These days the term is batted around a great deal, often with unspoken assumptions as to what mindfulness actually encompasses. We feel it’s important to clarify what we mean when we use it, as well as to distinguish mindfulness from mindfulness meditation.

Jon Kabat-Zinn’s definition of mindfulness is pretty simple: “paying attention in a particular way: on purpose, in the present moment, and nonjudgmentally” [1].

Bishop, et al. elucidate a bit more, specifying that there are two components to mindfulness:
“... self-regulation of attention so that it is maintained on immediate experience, thereby allowing for increased recognition of mental events in the present moment.”
“... adopting a particular orientation toward one’s experiences in the present moment, an orientation that is characterized by curiosity, openness, and acceptance” [2].

We differentiate mindfulness from mindfulness meditation insofar as mindfulness is more general (it can be done during any activity), whereas mindfulness meditation is typically done while sitting or walking and is wholly directed towards practicing and cultivating  mindfulness.


[1] Kabat-Zinn, Jon. Wherever you go, there you are: Mindfulness meditation in everyday life. Hachette UK, 2009.

[2] Bishop, Scott R., et al. "Mindfulness: A proposed operational definition." Clinical psychology: Science and practice 11.3 (2004): 230-241.


# Mindfulness Meditation

Programming and meditation actually have a fairly long history. ESR’s How To Become A Hacker, the first version of which appeared in 1996 but which harks back to hacker culture that began in the early 1960s, suggests “[studying] an actual meditation discipline” among its list of activities that support entering the hacker mindset. More recently, well-known programmer and creator of XP Kent Beck notes that meditation makes a big difference in his life.


There are many types of meditation and people hold meditation in many different ways. We suggest starting mindfulness meditation not because it’s the “best”, but because we understand it to be particularly relevant to programming.
Mindfulness meditation affords us a time get outside of our normal modes of thinking. This is useful for many reasons, not least of which because it can give you a different perspective on the problems you’re working on solving. Setting aside this time allows us as programmers to care for what is, after all, our most valuable asset.
If you’re curious about scientific studies of mindfulness meditation, check out the appendix, where we’ve listed a sampling of publications that indicate the beneficial effects of mindfulness.


So, how can you start practicing mindfulness meditation? Many books, courses, and apps exist. A search for “mindfulness meditation instructions” turns up a number of free instructional articles. For a deeper exposition, a free, eight-week online MBSR course is available here: http://palousemindfulness.com/.


# Mindfulness of Task
When we’re trying to get stuff done as programmers we often have the following experience:
  * Begin working on a task.
  * Discover a subtask that we think would be good to do first.
  * Begin working on the subtask.
  * Discover a subtask of the subtask that we think would be good to do first.
  * Begin working on the subtask of the subtask.
  * Discover a subtask of the subtask of the subtask we think would be good to do first before anything else.
  * Repeat ad nauseam.

At some point, we lose track of why we’re doing what we’re doing. We lose sight of the larger picture. If somebody comes over and asks us “What are you working on?”, we have a hard time giving a concise answer, because we’ve lost track of the complicated path that led us here.

How can mindfulness help? By making an effort to consciously keep track of what we’ve done, what we’re currently doing, and why, we can navigate the complex web of problems and sub-problems.

When a new task comes up, we don’t blindly just start doing it. We might weigh the pros and cons of doing it now or postponing it. Is it necessary for us to complete the task right now? Often, the answer is no. And the time we use to complete the task will actually take away from the task we set out to complete.

Like many applications of mindfulness, maintaining this conscious awareness takes persistent effort. It’s easy to not slow down and make mental notes and evaluations about what we’re doing. But for complex tasks that are pushing the limit of what our working memory can keep track of, it’s really helpful.

## Suggested Practice:

  * Set out with a task.
  * Get clear on what you’re trying to achieve and how you’re trying to do it.
  * In one sentence or less, write down what you’re doing and why.
  * When you discover a subtask that must be completed in order to complete the original task, write down what you’re doing and why in one sentence or less.

It’s helpful to order tasks as stacks. Push and pop tasks as you discover and complete them.


# Mindfulness of Stress
Similarly to our energy level, it’s easy for us to lose track of our stress level while we’re programming. We get so zoomed into what we’re doing that we often don’t notice the physical and mental stress that we accumulate throughout the day.

Is this stress a given? We assert that at least some of it isn’t. By tracking how we feel throughout the day and making small adjustments to our posture and disposition, we’re able to reduce the amount of stress that accumulates.

To take an operant example, how are you feeling right now as you read this? Are you leaning in, straining a bit as you read? Or slouching in a such way that makes you a bit less energized than if you sit up straighter? Are you holding tension in your jaw or shoulders?

Try adjusting your body position a bit, or taking a breath and relaxing your focus to a more comfortable tenor. See if you can make yourself feel a little more at ease through these micro-adjustments.

It takes persistence to do this throughout the day, but these micro-adjustments can add up. Rather than sapping our energy and tightening our body throughout the day, we can work at a more even keel. We may find that at the end of the day we have more energy and contentment, rather than feeling drained and harried.

## Suggested Practice
  Set a timer for some short amount of time (e.g. 15 or 20 minutes) while you’re working. When the timer goes off, take stock of how your body and mind feel. Are there any adjustments you can make to reduce tension or improve clarity? Is there something you can do to make yourself feel a bit more at ease? Make the adjustments, reset the timer, and carry on.


# Mindfulness of Code Quality
As a rule, our worst code is written when we’re tired. We think “I should do this the right way, but I’m tired and it’s the end of the day. I’ll just do it the easy way instead. We’ll fix it later.” But later never comes.

While the aim of this type of thinking is to get stuff done, it often has the opposite effect. Why? Because you end up with code that isn’t as clear or as clean as it could be. Sure, you might save a little time right now. But when somebody comes back to that code, it’s going to take them extra time and effort to understand it. Hopefully at that point they take the time and effort to fix it. Otherwise, it will cost the next person who has to work on it extra time and effort. And so on.

Identifying when we’re writing sub-par code and doing something about it can actually be surprisingly hard. As programming is a demanding and focusing task, it’s easy for us to lose track of ourselves. This is particularly the case when we’re under time pressure to complete a project.

Diligently practicing mindfulness and maintaining some awareness of what we’re doing and why can help, though. A programmer who knows when it’s time to take a break or go home will be more efficient and productive over the long run than one who continually writes sub-optimal code.

## Suggested Practice
  As you near the end of your workday, check in with yourself periodically. You can set a timer if necessary. Close your eyes, feel into your body and mind. If you realize that you’re overly tired and writing code in a way that’s, um, *different* than how you normally do (e.g. not writing tests although you normally do), consider taking a break or calling it a day.


# Mindfulness of Communication
  In software development, good communication is hard. As programmers, we want to be accurate and efficient communicators. As teammates, we want to helpful and receptive. As humans, we want to have fun. We have a lot to keep track of and it’s easy to lose track of ourselves in the process.

Practicing mindfulness of communication involves self-monitoring while in discussion or writing an email. We choose to reserve some part of our awareness for keeping track of how we’re feeling. Did my shoulders tighten up when someone criticized my code? Do I feel nervous while writing an email to my manager? Am I heading towards violent agreement in this discussion?

Noticing these internal phenomena can give us more flexibility in how we participate in communication. We can take a breath and, instead of being carried away by them, respond in a way that is more useful than our initial reaction might’ve been. We can have more space, ease, and freedom in our interactions.

## Suggested Practice
  Email writing is a good place to begin practicing mindfulness of communication because you can take as much time as you need to be aware of your body and mind.

While writing a non-trivial email, check in with how you feel every few sentences. If you notice you’re leaning towards the screen or emotionally activated, try to taking a breath and giving yourself a moment to understand what’s happening within you. Perhaps when you do this you’ll be able to relax a bit and continue writing with more ease and clarity.


# Appendix
## Benefits of a regular mindfulness meditation practice
  * Attention: [Mindfulness training modifies subsystems of attention](http://download.springer.com/static/pdf/993/art%253A10.3758%252FCABN.7.2.109.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.3758%2FCABN.7.2.109&token2=exp=1478195731~acl=%2Fstatic%2Fpdf%2F993%2Fart%25253A10.3758%25252FCABN.7.2.109.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.3758%252FCABN.7.2.109*~hmac=dc0f7191df23a1a5ee411913d0441bdd4dcd7afc859015d486b88736517130fe).
  * Attention, Information processing: [Mental Training Affects Distribution of Limited Brain Resources](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.0050138).
  * Emotional regulation: [Mindfulness meditation and reduced emotional interference on a cognitive task](http://link.springer.com/article/10.1007/s11031-007-9076-7).
  * Stress reduction, perceived well-being: [Mindfulness-Based Stress Reduction for Stress Management in Healthy People: A Review and Meta-Analysis, Relationships between mindfulness practice and levels of mindfulness, medical and psychological symptoms and well-being in a mindfulness-based stress reduction program)](http://online.liebertpub.com/doi/abs/10.1089/acm.2008.0495).
  * Immune function: [Alterations in Brain and Immune Function Produced by Mindfulness Meditation](https://www.ncbi.nlm.nih.gov/pubmed/12883106).
  * Reduction of cortisol, blood pressure: [One year pre–post intervention follow-up of psychological, immune, endocrine and blood pressure outcomes of mindfulness-based stress reduction (MBSR) in breast and prostate cancer outpatients](http://www.sciencedirect.com/science/article/pii/S0889159107000852).


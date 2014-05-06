Instrumentation as Living Documentation: Teaching Humans About Complex Systems
==============================================================================

:Authors: Brian Troutwine
:Time: 10:40 - 11:20
:Session:
:Link:

Troutwine is a software engineer: he writes software that talks to
other software, not necessarily end users. These are real time,
distributed systems, and he currently writes this software for Ad
Roll. That might seem like an odd fit, but advertising is changing
from large accounts that spend $10,000 per month on print advertising
to small, real-time bidding on ad slots (ie, $10/month on advertising
for fork bracelets on Etsy). The problem is a low latency, firm
real-time system, with non-smooth traffic patterns. This is considered
a Complex System.

Complex systems have non-linear feedback that are tightly coupled to
external systems. They're difficult to model and understand. They
often try to solve "wicked problems" [as described by C. West
Churchman]. Complex systems fail in catastrophic ways, and when they
do, they often create problems worse than those they set out to solve.

It turns out that just because we make something doesn't mean we
understand it (see Carlos Bueno, "Mature Optimization Handbook"). The
key challenge is actually maintaining and increasing our understanding
of the problem *and* the solution. So we write documentation. (Which
is troublesome, since communicating about these complex systems are
difficult to communicate about.)

Miscommunications are accidents in the making: the Challenger disaster
happened because there was miscommunication about the temperature
constraints on the O ring. If you don't know how a system *should*
behave, you can't say how it shouldn't or isn't behaving.  And the
documentation doesn't keep up with with the system.

Eric Schlosser, "Command and Control"

So if complex systems are so difficult to build and maintain and
document, what can we do?

Instrumentation reflects the reality of the system *as it is*, not as
we believe or expect it to be. Exploration guided by instrumentation,
done honestly, guides us to a better understanding of the system.

[Instrumentation case studies.]

And it's possible to have too little information from instrumentation,
or even too much (3 Mile Island example). Too much information hinders
interpretation. Instrumentation isn't a panacea. It's also software
itself, so *it's* susceptible to bugs, as well!

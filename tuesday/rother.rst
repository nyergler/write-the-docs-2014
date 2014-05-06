We Strongly Recommend You Write Best Practices
==============================================

:Authors: Lauren Rother
:Time: 11:20 - 11:40
:Session: http://docs.writethedocs.org/2014/na/talks/#lauren-rother-we-strongly-recommend-you-write-best-practices
:Link:

Works on Puppet Forge at Puppet Labs; Forge is a tool for hosting user
contributed modules and discovery. As the Forge has grown, users have
been asking for Puppet endorsed best practices and practices.
Documentation at Puppet Labs is embedded with engineering, so the
content is developed jointly with engineers who are writing Puppet
modules.

Puppet users have different needs, workflows, and most importantly,
different levels of experiences. The experiment was the "Beginner's
Guide to Modules", targeting novice users. They've chosen to target
different levels of user experience as the primary differentiator.

In the first version, they dumped everything they thought users might
ask or wnat to know into a document, then organized it into what felt
like logical sections using a textbook-like approach. The problem was
that it was overwhelming. The large paragraphs of text felt like they
were difficult to enter into and really understand. The solution was
to provide Orientation: introductory sentences that describe what
you're about to read, and sign-posts along the way to orient yourself.
("Hrm, I was supposed to know how to scope a module after reading this
section; did I actually learn that?").

They'd initially rejected this as overly-verbose and excessive text,
but what they discovered was that it makes the document more
accessible. This is true for novices -- who get some context as they
read -- as well as more experienced users -- who can use the signposts
as a way to jump over content they're already familiar with. [NB: This
means it's really important that the signposts are *accurate*.]

But even with smaller paragraphs, introductory sentences, and
sub-headings, it was difficult to locate distinct items. It was better
for the intial read, but still challenging when you returned to the
document and wanted to pick up where you left off. It was readable,
but not usable.

Thinking about the problem, Lauren realized that they were writing a
treatise, not a guidebook: something you read as a challenge, not
something that you return to again and again.

Best practices are often really a step by step guide, just like NKOTB
told us.

The final iteration has a table of contents, headings, introductory
sentences, steps (which makes it easy to write the TOC), and
*examples*. Interestingly, the process of putting the guide into
steps made it easier to add more examples, which give context and
background that words can not.

There's still room for improvement: the beginner's guide works well
and provides a good overview, but it's very high level. It glosses
over questions that will come up very quickly as users get up to speed
on Puppet modules.

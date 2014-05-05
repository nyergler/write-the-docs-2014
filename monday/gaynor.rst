Documenting Domain Specific Knowledge
=====================================

:Authors: Alex Gaynor
:Time: 13:50 - 14:10
:Session:
:Link: http://speakerdeck.com/alex/

Alex got his start writing software working on the Django project, a
project with a very strong culture of documentation. So what do users
come to the documentation looking for? Some users just want the
details. Alex isn't concerned with them: they usually have lots of
context to understand what's being written, and they're primarily
concerned with the completeness of the documentation. But what about
the people who come to the documentation who *don't* know about the
request/response cycle, or about how the web works? It's not clear how
well the tutorial really works for them (probably not very well).

Alex has been working on a Python cryptography library, and most users
just want the documentation to tell them what to do, without gaining
actual deep knowledge.

Can you document around a usability problem? Perhaps. What you can't
document around is their assumptions: if you don't shock them out of
their assumptions, and your software doesn't conform to those
assumptions, you'll just create frustration.

So documentation and design are a partnership.

Pick an audience. That's the audience you'll write software for.
"People who use my software" is not an audience; an audience is a set
of knowledge and background. Sometimes you'll need to write
documentation multiple times for multiple audiences. You'll need to
partition documentation between those audiences (this can be
challenging; one model is the software layer model, which is a good
way to separate users from experts).

Being able to write documentation that you can read top to bottom --
"straight line documentation" -- is incredibly valuable. Writing in a
reference style, with lots of links, is difficult to digest. Those
links should be optional for most users.

You should also eliminate assumptions you make as you're writing
documentation. Remove jargon, wherever possible, and when it's not
possible, the explanation should be front and center. Warnings about
using your tool the *right* way should **not** be buried in a link.
And of course, the design of your code should back up your
documentation, and provide sane defaults.

Your documentation should also enable use cases. Most people approach
documentation trying to solve a specific problem. Figure out what
those are, and write your documentation *for them*.

Composition is great for building software, but it can be problematic
for documentation, where users might not know how to connect the dots.
*Connecting the dots is your job as an author.* You can test whether
you've succeeded by testing your documentation with real users. When
they reach for Google, that's a documentation bug.

Nothing of consequence should depend on something the users doesn't
know they don't know. Your software (and documentation) can guide
them: make recommendations, not defaults, so that users are aware when
they're making a choice, and learn more about what they might not
know.

A tutorial should give users multiple, easy wins, preferrably with
less than 30 minutes of work. Give them points to stop and rest and
celebrate their progress.

Your users will never care about your domain the way you do.

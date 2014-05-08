Putting the (docs) Cart Before the (standards) Horse
====================================================

:Authors: Drew Jaynes
:Time: 9:00 - 9:20
:Session: http://docs.writethedocs.org/2014/na/talks/#drew-jaynes-putting-the-docs-cart-before-the-standards-horse
:Link:

WordPress took 10 years of inline documentation in the code and
developed a standard from that. Historically there was very little
attention given to inline documentation. The phpDoc spec was followed
loosely, but the Codex (wiki) was still seen as the main entry point
for documentation.

The Codex is a 2300+ page wiki of manually curated content. Before
every release, the documentation team would get together and make a
list of pages that needed to be updated. As the rate of WordPress
releases increased, the pressure on the Codex/Documentation team
increased, to the point where it felt unsustainable.

About 8 months ago, the Codex team wanted to document all the hooks in
WordPress core. Rather than trying to fit the WordPress hook
architecture into an existing standard, like phpDoc or [something
else], the team decided to survey existing practices in the code, and
developed Hook Docs.

Some background: In June 2013 WordPress Core went through some
evolution, and began recognizing teams of contributors. The Docs Team
came out of that, which gave the team its own blog, home_, etc. The
team held an informal summit at the Open Help Conference, where they
reviewed the Codex Survey conducted previously, and developed a
roadmap.

One of the primary goals of the roadmap was eliminating the Codex.
That goal spurred development of Hook Docs.

Eight months in, with the release of WordPress 3.9, all the hooks
(2200+) in WordPress Core have been documented. This is an increase
from 66k to 99k lines of documentation in the codebase. There were 40
new contributors over 3 releases, and version 1.0 of the code
reference is now live, and derived from the source code.

Developing a standard was obviously beneficial to the WordPress, even
if the project arrived there slightly later than other projects. (And
the Codex will become a giant 301 redirect.) The development of the
internal standard -- even though it diverges from some other PHP
practices -- is leading toward longer term consistency for the
project.

.. _home: http://make.wordpress.org/docs/

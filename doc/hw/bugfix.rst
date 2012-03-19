Homework - Bugfix
=================

Real learning in computing comes more from doing and less from studying.
Debugging, figuring out how some software works and how it doesn't, is an
interactive process that develops basic engineering practices and, in the open
source context, community engagement and collaboration.

Find a bug
----------

A bug can be anything: an unintended side-effect in a low-level routine, a
user-interface cleanup, a feature enhancement, grammatical errors or lack of
clarity in the project's documentation.

Broadly, you have two different options here.  You can

 - Find a known bug (or feature enhancement) listed in the project's bug
   tracker.
 - Find a bug yourself by using the software.

In the event of the second case, make sure you file the bug in the project's
tracker before proceeding.

You can fix a bug in any project you like.  The best to pick is something you *already
use*, something with which you're already familiar.  If you can't think of any
projects to investigate off the top of your head, here's a list of suggestions.

 - Scope the OpenHatch Volunteer Opportunity Finder for
   `Bite-sized Bugs <http://openhatch.org/search/?toughness=bitesize>`_
 - Use the search function at http://github.com/ and filter by language (to a
   language that you know).
 - Look up some of the bounties at Gun.io `<http://gun.io/>`_

Really, the sky is the limit here.

.. note:: For background, you might want to also check out the project on
   http://ohloh.net/.  It can help you characterize what kind of community
   orbits around your choice.

Use the Source, Luke
--------------------

Once you've identified a bug that needs fixing, you'll need to get ahold of the
source.  In most cases, the code for a project will be hosted on a forge and the
process of forking and cloning the source will be straightforward.   If you
forget how to do this for `github <http://github.com>`_, you can refer to
:doc:`fflight`.

For whatever project you've chosen, you should ask that project's community for
help.  Look for `IRC` channels and project mailing lists.  You'll be
communicating with developers who have a lot on their plate so make sure to `be
polite and leave your ego at the door
<http://maymay.net/blog/2009/02/11/how-to-start-contributing-to-open-source-projects/>`_.

Find the code related to the bug; use whatever code navigation tools you're
more familiar with.  The instructor's favorite method is:  ``grep -inr "some
string" project_src/``.

Fix the bug, this may require some thinking, and some more asking around.

Test your fix!  Project maintainers hate nothing more than receiving a patch
that breaks every other function of the project.  Often, projects have built-in
test suites.  If yours does, run it!

Prepare your patch with descriptive commit messages.  Follow the method for
submitting patches recommended by your project and submit!

Make sure the project community can easily understand what you did and
why you did it.

Make sure there is a reference in the tracked bug ticket to your patch (that is,
if the project maintains a bug tracker).

The Deliverable
---------------

Write a blog post about this process and provide relevant links where
possible to documentation.

 - A link to the patch(es) hosted somewhere on the web, usually forges provide
   the ability to link to changesets.
 - A link to any mailing list discussions archived on the web
 - Snippets of any relevant IRC conversations.

You will be graded on your post and the explanation of your process.  Extra
kudos (but not extra credit) for super epic patches.

An Afterthought (not required)
------------------------------

Once your patch has been accepted, mosey on over to http://ohloh.net.

 - Create an account
 - Find the project you patched

   - If it doesn't exist, you can add it yourself

 - "Claim your position" as the author of the commit(s) you sent in to increase
   your rank among open source developers of the world!

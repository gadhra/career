As the dust settles on Pangea and the final screws are tightened up, I wanted to take a second to illustrate some of the gains this considerable effort has brought to WIRED.

At the basic level, we consolidated 17 instances of Wordpress into one, unified codebase.  The original codebase on Wordpress stretched back roughly 8 years, and incorporated content from the 12 years before that.  In order to bring everything under a single umbrella, the tech team had to massage the data and contents of roughly 1.3 million pages,  including 340,000 blog posts.  The system was one of the most complex I have ever seen, with strange inter-dependencies and relationships throughout the system, stretching all the way back to the birth of the consumer Internet.

We’ve been putting out random fires from the migration for the past month, but all in all things are starting to die down to a dull roar.  So, for our collective investment of time and annoyance, what did we get?

**1.  A leaner, cleaner codebase that runs faster for the end user**

Pulling all the content into a single codebase allowed us to refactor and reanalyze a lot of the cruft that had accumulated on the website over the past score of years.  We were able to drop our homepage load time 13% (plenty of work still to be done – here’s where the redesign project will be particularly helpful); our gallery load time 62%; and our features (like Station to Station) by 72%.  This is just the beginning — the advantage of being on a single codebase is that we can now more easily identify bottlenecks (for example — we can see categories like Gadgetlab take the most application response time) and can tactically apply resources to optimizing that code.

**2.  A modern development environment for our technical team**

Pangea allowed us to shift into a proper, modern, sharable development environment with continuous integration, staged deployments, and a codebase that can be shared with and modified by the Conde Nast core development team.  This means we’ll be able to reap the benefits not only of what we’re working on, but also leverage the work done by the company more broadly.  

Additionally, the environment now allows us to repeat technical approaches and methods quickly and easily (this mostly applies to our award-winning features) as well as innovate and experiment with new, bleeding-edge technical approaches without needing to move mountains to do so.   This environment unfetters developers and gets technology “out of their way,” allowing them to create the next best thing.

**3.  A more stable and secure world for our content to live in**

Prior to the launch of Pangea, our reporting tools would consistently report an average error rate of 2.94%, sometimes going as high as 10% — this means that in a month where we got 100 million pageviews, between 2.9 million and 10 million of those requests would kick an error of some sort.  I’m happy to report that, at last check, our error rate has dropped to 0.009%, meaning we are more confident in our codebase and in our technical approach to problems.  Other than the obvious potential of a high rate of error destabilizing the entire environment, code that contains a number of errors also offers a plethora of vectors of attack for hackers, which can be extremely difficult to track down. 

Cleaning up all these errors, optimizing the codebase, and rearchitecting the server structure dropped the server response time from 2.25s to 584ms — an improvement of roughly 400%.  This means the server will respond to requests significantly faster than before, which will reduce overall page load time.  There’s still more work to do here — we’d like to see the server response time at around 200ms — but the basic groundwork has been laid.

**4.  A stepping-stone for the future**

With Pangea firmly behind us, we can now look to slice and dice our content in new ways.  We have set the stage for our content (what you’re reading) to be decoupled from the display (how it looks and how you interact with it), allowing the extremely skilled design team at WIRED to translate their concepts into reality without the legion of technical hurdles they faced in the past. 

As part of this, we are now able to parse our content by keywords very easily.  If we wished to sell a collection of “Apple” articles starting tomorrow, that would be a possibility.  Previously all content resided in its own vertical, and it was a heavy list to create a custom content hub.

Finally, as something near and dear to my heart, this merging of the codebase allowed us to bring all of our technical skills into alignment.  Instead of being a Babel of developers with their own area of expertise (Java, PHP, jQuery, Oracle, MySQL, etc.), we are now all working in the same language on the same codebase, meaning we can apply resources across all of our offerings instead of needing to allocate folks to projects based on skillset.  

This common core has additional value — because everyone is essentially starting from the same point, it becomes much easier to pivot the development team towards newer technologies as a whole, rather than piecemeal.  This allows us to get in front of the vast array of new tech coming up.  

Thanks!

We know this project wasn’t the sexiest thing; a lot of it had to be taken on faith from managers, content creators, designers, and advertising and sales folks.  We want to thank everyone who believed in us, who backed us up, and who gave us the time and space we needed to get this done.  We’re looking forward to what’s next! 


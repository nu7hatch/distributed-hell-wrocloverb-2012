!SLIDE
# Optimize all the things!

<note>
  Uhm, not really...
</note>

!SLIDE
<blockquote>
  Prototype, then polish. Get it working before you optimize it.
  <author>Rob Pike</author>
</blockquote>

<note>
  Every one knows about it right! Red-Green-Refactor cycle.
</note>

!SLIDE
# Measure!

<note>
  We should keep things simple, and not optimize them at all until we need that.
</note>

!SLIDE
<blockquote>
  Measure. Don't tune for speed until you've measured (...)
  <author>Rob Pike</author>
</blockquote>

<note>
  We have to measure our systems and optimize only evident bottlenecks.
  Premature optimization is source of the all evil. You know that. Use it
  wisely! And keep it simple anyway...
</note>

!SLIDE
<blockquote>
  Fancy algorithms are buggier than simple ones, and (...) harder
  to implement. Use simple algorithms as well as simple data structures.
  <author>Rob Pike</author>
</blockquote>

<note>
  Remember that you can scale everything up easily using the hardware,
  even temporarily... but... only when your system is composed from
  the parts which...
</note>

!SLIDE
# Do one thing right!

<note>
  Again, application splitted up into the web-services is easier
  to measure and optimize. Sometimes, again, we don't have to 
  optimize it at all. We can just scale up number of instances
  handling specific application and we're done. 
</note>

!SLIDE
# Hardware vs. Software

<note>
  You know, I still like to tweak things up. But now when I understand
  business rules behind all the systems, I stopped doing this in a clients
  work. 37signals also knows about it very well, that's why all their
  apps are scalled through hardware.
  
  The only bad things about them is that they are using humongous amount
  of RAM to handle their fat and overwhelming Rails apps, so they can't
  use cloud coputing effectively!
</note>

!SLIDE
# R.I.P Ruby on Rails

<note>
  No offense guys... Rails must die!
</note>

!SLIDE
# Long live web-services

<note>
  Keep it simple... Enjoy the power!
</note>

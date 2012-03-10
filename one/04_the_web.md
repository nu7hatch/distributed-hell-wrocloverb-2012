!SLIDE
# Long time ago, in a galaxy far away...

<note>
  Over the past years the Web was growing insanely fast. Just few years ago
  high scale systems were almost reserved for financial services or reaserch
  engines. There was very few web based high scale systems.
</note>

!SLIDE
# Suddenly, Web 2.0 appears...

<note>
  And then, bang... people discovered blogs, social networks, online
  collaboration platforms etc, etc.
</note>

!SLIDE
# Don't worry, I'm from the Internet!

<note>
  At the same time, more and more people started joining the global 
  network, generating higher traffic, having higher expectations, and well
  sometimes simply polluting the internet.
  
  And now, we have to deal with it...
</note>

!SLIDE
# Distributed Nyan nyan cat!

<note>
  We have to deal with billions of trolls watching nyan nyan cat or
  tweeting about "Friday!", or doing lot of different weird things...
</note>

!SLIDE
# Optimize all the things!

<note>
  Some time ago, when I didn't understand the unix philosophy very well yet,
  I was crazy about optimizing things. I was tweaking up everything, thus
  systems I was working on were big, hard to maintain, more expensive in
  time... and at the end, actually slower than it should be and hard
  to improve.

  Well, that was before I became awesome....
</note>

!SLIDE
<blockquote>
  The most powerfull optimization technique in any programmer's
  toolbox is do nothing...
</blockquote>

<note>
  Premature optimization is a source of all evil, everyone know about
  that. All of us know as well that we should keep things simple, small
  and maintainable...
</note>

!SLIDE
# Small is beautifull

<note>
  "Małe jest piękne", like one polish movie said... Maybe it's not always
  true in real life, but applies perfectly to software development...

  Small systems are easier to develop, easier to maintain, easier to learn.
</note>

!SLIDE
# Do one thing right!

<note>
  Unix hackers understand this long time ago. First they split up programs
  into subprograms. They split up big applications into libraries.
  Then, they built small and reusable tools based on those libraries...

  On early begginings of unix development, Dennis Ritchie said to 
  all the people around, that function calls are super cheap in C...
  So everyone split up big spaghetti code into functions. Later they
  discovered that Dennis lied to them, but it was too late. Most of
  the code was written this way, it was slower, but super easy to maintain.
  
  That's why sometimes...
</note>

!SLIDE
# Worse is better

<note>
  Yeah... sometimes...
</note>

!SLIDE
# R.I.P Ruby on Rails

<note>
  Yes, I really think so, I really believe that Rails is on a way to die.
  It may take a while, but it's unstoppable.

  Web applications are very similar to operating systems. They do many 
  small things, they manage users, they allow to post articles, comments,
  talk with other people, and so on.
  
  Currently, most of Web apps are big, monolythic systems. Big Rails 
  application containing all the model entities, http responses in 
  different formats, with some javascript layer included... That's not
  the way.
</note>

!SLIDE
# Long live Web-services!

<note>
  Do one thing right. The greatest projects, slowly start understanding 
  that. For example, the github's API is built from 30 different sinatra
  applications. Heroku separated their platform in bunch of small 
  webservices, daemons and tools. Linkedin serves bunch of things using
  small sinatra services in JRuby.

  Rails is fast at development speed, so that's why is preferred by many
  startup companies to build the things. Well, most of them are failing
  horribly, that's why they don't have to scale those apps. Those who
  have to, already know that Rails is not enough...
</note>

!SLIDE
# Do one thing right...

<note>
  Once again, small pieces of code, smaller applications are easier
  to learn and maintain. They are easier to measure and scale, which
  is the most important thing. Finally, they are even easier to test.
  I'll tell you a word about it later.
</note>

!SLIDE
# Keep it simple

<note>
  Lot of people is afraid to admit that, to say straight that Rails
  doesn't match current requirements of the market anymore. With all the 
  respect, Ruby on Rails   was amazing innovation few years ago, it fit 
  into the market of web startups, it brought some fresh air to the web 
  development implementing some of the Unix principles and promoting the 
  others, like DRY and Keep it simple...
</note>

!SLIDE
# Bitch slap!

<note>
  Now Rails even tough it has been modularized and refactored few times,
  it growth into a big sledghehammer, not so simple to setup, getting harder
  to develop and totally hard to maintain.
  
  The Unix philosophy is coming back now, and bitch slaping it horribly.
</note>

!SLIDE
<blockquote>
  Losers live in the past. Winners learn from the past and enjoy working in 
  the present toward the future.
  <author>Denis Waitley</author>
</blockquote>

!SLIDE
<blockquote>
  The best way to predict the future is to invent it.
  <author>Alan Key</author>
</blockquote>

!SLIDE
# Long live web-services!

<note>
  Distributed web-services are the future! It's already here. Invented 40 years ago.
</note>

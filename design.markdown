---
layout: page
---

# A Ruby Design Process

Ruby is a complex, mature programming language supported on numerous operating
systems (e.g. Unix, Linux, Windows, etc.) and on diverse platforms (e.g. JVM,
CLR, Smalltalk, etc.).

The Ruby programming language boasts at least six significant, full-featured
implementations, including [MRI](http://ruby-lang.org),
[JRuby](http://jruby.org/), [Rubinius](http://rubini.us/),
[IronRuby](http://ironruby.net/), [MacRuby](http://macruby.org/), and
[MagLev](http://maglev.github.com/). There are also several special-purpose
derivatives of Ruby, include [mruby](https://github.com/mruby/mruby),
[RubyMotion](http://www.rubymotion.com/), and
[MobiRuby](http://mobiruby.org/).

_Ruby has no formal design process, despite Ruby being an industrial strength
programming language, having hundreds of millions of dollars invested in
businesses built around the language. There is no process to maintain unity of
the Ruby language. There is no definitive resource defining Ruby.  Developers
can only support multiple Ruby implementations with trial and error._

At RubyConf 2012, Brian Ford [presented a
talk](http://www.confreaks.com/videos/1278-rubyconf2012-toward-a-design-for-ruby)
advocating a Ruby design process. The proposed process has been [detailed in a
blog post](http://brixen.io/2012/12/11/a-ruby-design-process).

The Ruby design process is summarized below. Please see the blog post for
elaboration and clarification.

1. A _Ruby Design Council_ made up of representatives from any significant
   Ruby implementation, where significant means able to run a base level of
   RubySpec (which is to be determined).
1. A proposal for a Ruby change can be submitted by any member of the Ruby
   Design Council. If a member of the larger Ruby community wishes to submit a
   proposal, they must work with a member of the Council.
1. The proposal must meet the following criteria:
    1. An explanation, written in English, of the change, what use cases or
       problems motivates the change, how existing libraries, frameworks, or
       applications may be affected.
    1. Complete documentation, written in English, describing all relevant
       aspects of the change, including documentation for any specific methods
       whose behavior changes or behavior of new methods that are added.
    1. RubySpecs that completely describe the behavior of the change.
1. When the Council is presented with a proposal that meets the above
   criteria, any member can decide that the proposal fails to make a case that
   justifies the effort to implement the feature. Such veto must explain in
   depth why the proposed change is unsuitable for Ruby. The member submitting
   the proposal can address the deficiencies and resubmit.
1. If a proposal is accepted for consideration, all Council members must
   implement the feature so that it passes the RubySpecs provided.
1. Once all Council members have implemented the feature, the feature can be
   discussed in concrete terms. Any implementation, platform, or performance
   concerns can be addressed. Negative or positive impact on existing
   libraries, frameworks or applications can be clearly and precisely
   evaluated.
1. Finally, a vote on the proposed change is taken. Each implementation gets
   one vote. Only changes that receive approval from all Council members
   become the definition of Ruby.

---

_**If you support the design process for Ruby outlined above, please let your
voice be heard by signing below.**_

<div class="signatures">
  <iframe src="//signatures.rubyspec.org" frameborder="0" scrolling="no"></iframe>
</div>

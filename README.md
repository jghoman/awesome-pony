[<img src="https://github.com/jghoman/awesome-pony/raw/master/ponylang-logo.jpg" align="right">](https://www.ponylang.org/)
# awesome-pony [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Curated resources about the Pony programming language, learning resources for it and interesting systems written in it.

## Vital links
* [ponylang.org](https://www.ponylang.org/) - Main language and project website.
* [github](https://github.com/ponylang) - Pony organization github, including the language repo.
* [mailing list archive](https://pony.groups.io/g/user) - Quick way to join the mailing list or peruse the archives.
* [Zulip chat](https://ponylang.zulipchat.com/login/) - Chat with users and core developers.

## Interesting Pony libraries
* [pony-kafka](https://github.com/WallarooLabs/pony-kafka) - Pure pony implementation of an [Apache Kafka](https://kafka.apache.org/) client.  Currently supports many, but not all features of the Scala/Java client maintained by the ASF project.
* [ponylang-linal](https://github.com/dougmacdoug/ponylang-linal) - Linear algebra library supporting two- and three-dimensional operations. Under active development.

## Tutorials and focused blog posts
* [Systems Languages: An Experience Report](https://blog.usejournal.com/systems-languages-an-experience-report-d008b2b12628) - [Sargun Dhillon](https://twitter.com/sargun) includes his experience with trying to use Rust, among several other newer systems languages, to write a fairly simple signal handler for container shutdowns.
* [Pony Considerations](https://gist.github.com/aturley/49b60c98306d90ffc2f981515827b005) - Brief but useful Github gist with a tour of tools, editors, IDE configurations, etc. for getting started with Pony by [Casio Juarez](https://twitter.com/casio_juarez).
* [How to Train Your Pony](https://paul.lietar.net/2018/03/how-to-train-your-pony-introduction/) - First in a series on Pony's type system by [Paul Liétar](https://twitter.com/lietarp).  This entry covers how Pony prevents data races.
* [Chris Double](https://twitter.com/doublec) maintains an [excellent blog](https://bluishcoder.co.nz/index.html) that covers lots of programming languages and has an excellent collection of [Pony posts](https://bluishcoder.co.nz/tags/pony/index.html), including (but not limited to):
   * [Reference Capabilities, Consume and Recover in Pony](https://bluishcoder.co.nz/2017/07/31/reference_capabilities_consume_recover_in_pony.html)
   * [Borrowing in Pony](https://bluishcoder.co.nz/2016/07/18/borrowing-in-pony.html)
   * [Exploring actors in Pony](https://bluishcoder.co.nz/2016/05/11/exploring-actors-in-pony.html)
* [Ponylang Cheatsheet](https://www.ponylang.io/media/cheatsheet/pony-cheat-sheet.pdf) - One page PDF that covers all the core syntax and concepts.

## Pony community and history
* [An Early History of Pony](https://www.ponylang.org/blog/2017/05/an-early-history-of-pony/) by [Sylvan Clebsch](https://github.com/sylvanc) and [Sean Allen](https://twitter.com/SeanTAllen).  Discusses the origins of Pony and what prompted its creation.
* [Message Passing and the Actor Model](http://dist-prog-book.com/chapter/3/message-passing.html) by [Nathaniel Dempkowski](https://twitter.com/natdempk).  While this in-depth article does not deal with Pony directly, it is a good introduction to the actor model paradigm, covering its history and major implementations.

## Folks who tweet interesting things about Pony
* [Sean T Allen](https://twitter.com/SeanTAllen) - VP of Engineering at [Wallaroo Labs](https://www.wallaroolabs.com/) and one of the early contributors to Pony.

## Slide Decks and Recorded talks
* [The Wide World of Actors, or, Can I Have an Erlang Pony?](https://github.com/slfritchie/wide-world-of-actors/blob/master/can-i-have-an-erlang-pony.pdf) - [Scott L. Fritchie](https://twitter.com/slfritchie) has created a deck that compares Pony to another Actor-based language, Erlang and its VM, BEAM.
* [Pony: How I learned to stop worrying and embrace an unproven technology](https://www.infoq.com/presentations/pony-wallaroo) - [Sean Allen](https://twitter.com/SeanTAllen) has a brief overview of Pony.  This same material is covered on the official Pony site, but the talk is useful for those that prefer to follow visually.
* [Why Pony](https://www.youtube.com/watch?v=0XFhTrtOGK4) - Also by [Sean Allen](https://twitter.com/SeanTAllen).  Short talk focused on Pony's concurrency model.  Slides are available [here](https://speakerdeck.com/seantallen/why-pony).

## Academic Papers
* [Ownership and Reference Counting based Garbage Collection in the Actor World](https://www.doc.ic.ac.uk/~scd/icooolps15_GC.pdf) - 
by Sylvan Clebsch, Sebastian Blessing, Juliana Franco and Sophia Drossopoulou.  This paper describes the ORCA garbage collection scheme the Pony team has developed.  ORCA leverages Pony's concepts of actors and differentiated data sharing.

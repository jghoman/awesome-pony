[<img src="https://github.com/jghoman/awesome-pony/raw/master/ponylang-logo.jpg" align="right">](https://www.ponylang.org/)
# awesome-pony [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Curated resources about the Pony programming language, learning resources for it and interesting systems written in it.

## Vital links
* [ponylang.org](https://www.ponylang.org/) - Main language and project website.
* [github](https://github.com/ponylang) - Pony organization github, including the language repo.

## Interesting Pony libraries
* [pony-kafka](https://github.com/WallarooLabs/pony-kafka) - Pure pony implementation of an [Apache Kafka](https://kafka.apache.org/) client.  Currently supports many, but not all features of the Scala/Java client maintained by the ASF project.

## Tutorials and focused blog posts
* [Chris Double](https://twitter.com/doublec) maintains an [excellent blog](https://bluishcoder.co.nz/index.html) that covers lots of programming languages and has an excellent collection of [Pony posts](https://bluishcoder.co.nz/tags/pony/index.html), including (but not limited to):
   * [Reference Capabilities, Consume and Recover in Pony](https://bluishcoder.co.nz/2017/07/31/reference_capabilities_consume_recover_in_pony.html)
   * [Borrowing in Pony](https://bluishcoder.co.nz/2016/07/18/borrowing-in-pony.html)
   * [Exploring actors in Pony](https://bluishcoder.co.nz/2016/05/11/exploring-actors-in-pony.html)

## Pony community and history
* [An Early History of Pony](https://www.ponylang.org/blog/2017/05/an-early-history-of-pony/) by [Sylvan Clebsch](https://github.com/sylvanc) and [Sean Allen](https://twitter.com/SeanTAllen).  Discusses the origins of Pony and what prompted its creation.

## Folks who tweet interesting things about Pony
* [Sean T Allen](https://twitter.com/SeanTAllen) - VP of Engineering at [Wallaroo Labs](https://www.wallaroolabs.com/) and one of the early contributors to Pony.

## Recorded talks
* [Pony: How I learned to stop worrying and embrace an unproven technology](https://www.infoq.com/presentations/pony-wallaroo) - Sean Allen](https://twitter.com/SeanTAllen) has a brief overview of Pony.  This same material is covered on the official Pony site, but the talk is useful for those that prefer to follow visually.

## Academic Papers
* [Ownership and Reference Counting based Garbage Collection in the Actor World](https://www.doc.ic.ac.uk/~scd/icooolps15_GC.pdf) - 
by Sylvan Clebsch, Sebastian Blessing, Juliana Franco and Sophia Drossopoulou.  This paper describes the ORCA garbage collection scheme the Pony team has developed.  ORCA leverages Pony's concepts of actors and differentiated data sharing.

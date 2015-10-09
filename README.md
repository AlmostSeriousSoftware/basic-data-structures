# basic-data-structures
This repo contains some of the most commonly used data structures(from now on DS) in the CS world.
It also includes some of the most common algorithms to traverse said DSs.

## What to expect

Here you will find implementations of some of the most commonly used DSs. don't expect them to be exactly the same as the default language implementations nor to be the most efficient implementations. They are mostly *human readable* implementations.

All the DS implementations will come with an example usage. 

## Push Guidelines

In order for this repo to be a reliable source, you **must** follow the next guidelines if you are intending to push to it.

* The implementation language **must be** Java.
* Each DS must be on it's own package.
* Each package associated to a DS can have as many subpackages as needed and all the sources must be highly related to that DS.
  * Try to not make long paths of packages.
  * If you wish to write several implementations, you can make a *java interface*.
* If needed, you can import classes (as in java *import \<package\>.\<Class\>*) from other implemented DS but you **MUST NOT** copy them.
  * If there is a default library implementation of the secondary required DS (or a trivial algorithm), you should prefer it over the custom implementation ( Unless you have a great reason to not use it -*which must be highly documented*-).
  * You can find a list of the built-in DSs and the methods provided by the *Java Collections package* [here](http://java-performance.info/java-collections-overview/).
* Try to follow the most *Best Java Practices* you can.
* Prefer to use Generic Datatypes instead of Object datatype when possible.
* All the classes/methods/variables must be documented with short comments, the easier to understand the better. Don't confuse *documented* with *exaggeratedly verbose documentation*
  * Documentation must be either in english or spanish, if they are in spanish, please speak promptly with another team member asking him to translate it.
  * Don't worry if your english isn't good enough, just make sure you make your best effort, we won't judge.
  * Remember to document the algorithm performance using the Big O notation.
  * If possible, try to explain when it's a good idea to use the DS or when not.
  * **If you know who invented the algorithm/DS you are implementing, you MUST include his name on the documentation.**
  * If you took part of the code from a book or somewhere else, you MUST specify it in the documentation, also make sure you have the right (as in legal right) to copy it. 
* Prefer to implement a human readable DS/algorithm than a *highly-complex-hard-to-understand* algorithm.
  * If you really decide to go for the hard-to-understand implementation, it's big O complexity must be at least an order down than the *human readable* implementation (More efficient).

Also keep in mind that:

* For every implementation, you **must** include **at least** one example. The more the better.
* All the DS implementations and their algorithms must go in a package inside the *DS* package
* All the examples must be in a package with the name of the DS on the *examples* package.
* The examples must be documented as well.


This readme is under construction, feel free to modify it as needed.

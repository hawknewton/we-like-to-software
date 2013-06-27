* Prepature Optimization -- Shooting fish in a barrel is easy, provided you can find the right barrel
  * Story (at a previous company) about hashmap on fire and .empty()
  * Story (at a previous company) about wanting to make parallalize calls
  * Caches -- special place in hell for unneeded caches
    * Issues with cluster synchronization
    * Cache invalication
    * Operational overhead
    * Talk about slow services and SLAs
  * Implement, measure, iterate
  * Don't fix a problem you don't have
  * Measure often -- In the land of the blind the one-eyed man is king
                     In the land of the blind the one-eyed man king is stoned to death
                     (include screen cap)

* Misunderstood or outdated best practices
  * Factory or (worse) AbstractFactory with only one implementation
    This happens today more than you might expect, especially in
    data acces layers
      * Interface, abstract class, factory, implementation
  * Coding to an interface instead vs an implementation.
    GOF came out in 1995, before refactoring IDEs became popular
  * org.w3c.dom.*
    Good thing this came along, who knows what I would have done
    without an XML parser inteface that likes to change implementation
    for no decernable reason
  * OCP

* Unclear or unchallenged requirements
  * Story about CBLT cache hit rates
  * Story about polishing cannonballs


* Closing
  * The fox and the cat
  * Do complex problems demand complex solutions? -- look at maven
  * K.I.S.S
  * Simplicity is the ultimate sophistication -- Leonardo da Vinci
  * Less is more -- Mies Van Der Rohe


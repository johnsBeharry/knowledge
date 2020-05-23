###### Formal Verification of Code

[1a]: https://en.wikipedia.org/wiki/Formal_verification
[1b]: https://en.wikipedia.org/wiki/Finite-state_machine	"Finite State Machine"
[1c]: https://en.wikipedia.org/wiki/Transition_system	"Transition system"

###### Hash Table

A associative array that utilises a hashing function to generate the keys.

[2a]: https://en.wikipedia.org/wiki/Hash_table "Hash Map / Hash Table"

###### DHTs characteristically emphasize the following properties:

- [Autonomy and decentralization](https://en.wikipedia.org/wiki/Decentralized_computing): the nodes collectively form the system without any central coordination.
- [Fault tolerance](https://en.wikipedia.org/wiki/Fault_tolerance): the system should be reliable (in some sense) even with nodes continuously joining, leaving, and failing.
- [Scalability](https://en.wikipedia.org/wiki/Scale_(computing)): the system should function efficiently even with thousands or millions of nodes.

A key technique used to achieve these goals is that any one node needs to coordinate with only a few other nodes in the system – most commonly, [O](https://en.wikipedia.org/wiki/Big_O_notation)(log *n*) of the n![n](https://wikimedia.org/api/rest_v1/media/math/render/svg/a601995d55609f2d9f5e233e36fbe9ea26011b3b) participants (see below) – so that only a limited amount of work needs to be done for each change in membership.

###### Streams

- Used often when needing to process a large amount of data that is not possible to store in memory.
- 
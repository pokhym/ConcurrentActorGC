# ConcurrentActorGC

This repository contains an executable specification of the algorithm linked in the sources.
In addition to this, this repository also contains the proof of properties such as completeness and soundess of the algorithm.

Note that the paper linked below is does not contain the final algorithm as optimizations have been made since its publication.
However, these optimizations will be included in the specfication.

# Files
G.maude: Contains the specification for the soup of messages and actors

msg.maude: Contains the specification for msgs

actor.maude: Contains the specification for actors

reference.maude: Contains the specification for references

util.maude: Contains the specification for utility modules.
Currently this only contains predicates and natural numbers.

Import order is shown below

		G.maude
			msg.maude
				actor.maude
					reference.maude
						util.maude

# Sources
Dan Plyukhin and Gul Agha. 2018. Concurrent garbage collection in the actor model. In Proceedings of the 8th ACM SIGPLAN International Workshop on Programming Based on Actors, Agents, and Decentralized Control (AGERE 2018). ACM, New York, NY, USA, 44-53. DOI: https://doi.org/10.1145/3281366.3281368
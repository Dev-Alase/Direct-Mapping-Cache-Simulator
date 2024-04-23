# Direct-Mapping-Cache-Simulator
It's a cache simulater. It simulates how do cache behave under direct mapping technique.

Brief Intro :-- 
CPU generates some word address from which data or instruction is needed to be fetched from the memory,that address will be first checked in to cache to see if it's already there.if it is it will be considered as cache hit,if it's not it will be a cahce miss.

Cache miss :-- 
There are two cercumstances when cache miss can occur --
  1) When there are no prior entries in the cache.
  2) when there is a entry in the cache at calculated index but it's tag bits are different than current one.( How it is a miss :-- CPU generates word address, but there are blocks stored in a cache which contains multiple words so the words in the same block will have same tag address )


Cache hit :--
If there is already a entry in the indexed place in the cache and it have same tag bits as the current one.

More on info : https://www.baeldung.com/cs/cache-direct-mapping

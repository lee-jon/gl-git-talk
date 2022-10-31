# Graph Theory

	A --- B --- D --- K
	 \     \         /
	  \     \       /
	   E --- F --- G --- J
      \   / \
       \ /   \
        H --- I

A graph is a structure in which a set of nodes (vertices) are in some sense related. 

   A --- B --- C

A is related to B. B to C. But A is not related to C. 

In CS we might label our nodes. 

   London --- Manchester

In a social graph we might label the edge

   Bob ---(likes)--- Jim

Some edges can be DIRECTIONAL

## Reachability
With directed graphs, each node has a property of reachability

            A <-- B --- C 
           /
    D <-- E --- F <-- G



Download Link : https://programming.engineering/product/ve489-computer-networks-homework-set-5/

# Ve489-Computer-Networks-Homework-Set-5
Ve489 Computer Networks Homework Set 5



    What principle is followed by all routing protocols?

    Study distance vector routing and answer the following questions:

        What is a distance vector?

        Is routing path setup of distance vector started from source or destination?

        Why Bellman‐Ford algorithm can be used for distance vector routing?

        What are the advantages of distance vector routing?

        What are the shortcomings?

    Considering the following network topology, suppose a routing table needs to be built from all nodes to Node 5, please use distance vector routing to complete the task. Show the steps as shown in the table.

        1
        	

        5
        		

        3
        	

        3
        	

        1
        		

        2
        		

        4
        		

        4
        		

        6

        2
        	

        4
        	
        	

        2
        		

        5
        	

        1
        	

        3
        	
        			

Iteration
	

Node 1
	

Node 2
	

Node 3
	

Node 4
	

Node 6

5
					

Initial
	

(-1, )
	

(-1, )
	

(-1, )
	

(-1, )
	

(-1, )
					

1
	

(-1, inf)
	

(5,3)
	

-1, inf
	

5, 4
	

5,1

2
	

2,7
	

5,3
	

6,3
	

5,4
	

5,1
					

3
	

2,7
	

5,3
	

6,3
	

5,4
	

5,1

    Study the link state routing protocol and answer the following questions:

        Is link state routing a centralized or distributed scheme?

        What algorithm is followed in the link state routing?

        Link state routing is a source based routing protocol. After a routing table is built up on a source, it is necessary to add the entire routing path into the packet header? Why?

        What are the pros and cons of the link state routing protocol?

    What are the typical schemes for packet‐level traffic management?

    How flow‐level traffic management is related packet‐level traffic management?

    Leaky bucket algorithm is useful for flow level traffic management. Assume the incremental per arrival, I, is 4 packet times; leaky bucket depth, L+I, is 10 packet times (i.e., L = 6). The depletion rate is 1 packet per unit time.

    Given the packet arrivals in figure (a), please draw the bucket content curve in figure (b).

    Please mark the non‐conforming packets in figure (a)

                        (b)
                        	

                        Time

8. Explain the major differences between the leaky bucket and the token bucket algorithms.

# Designing-a-Kohonen-self-organizing-map-SOM-
Designing a Kohonen self organizing map (SOM), which gives as an output some shades of color mapped over 100 by 100 grid of neurones. The training input of the SOM are 24 colors (use shades of red, green, blue, with some yellow, teal and pink)
Using a time varying learning rate 

        πΆ(π) = πΆππππ(βπ/π»)
        
,where k is the current training epoch (starts withepoch 0), πΆπ = π. π , and T is the Total number of training epochs equal to 1000. Note that the epoch training involves all twenty four input samples for the 24 chosen colors to the network. Initial weights are randomized. The topological neighbourhood π΅π,π(π) of node (j) around the winning unit (i) is given by
       
       πi,j(π) = exp(-dsquare i,j / 2πsquare(π))
Where

      π(π) = π0exp(βπ/π)

And πi,j is the distance between the winning node i and surrounding node j.

a) Generate a figure of the original grid (random weights) followed by figures of the SOM after 20, 40, 100, 1000 epochs. Change the value of π0 = 1, 10, 30, 50, 70.

b) Conclusions are drawn on how the output changes with π0 and the number of epochs.

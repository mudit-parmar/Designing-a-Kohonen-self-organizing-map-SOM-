# Designing-a-Kohonen-self-organizing-map-SOM-
Designing a Kohonen self organizing map (SOM), which gives as an output some shades of color mapped over 100 by 100 grid of neurones. The training input of the SOM are 24 colors (use shades of red, green, blue, with some yellow, teal and pink)
Using a time varying learning rate 

        𝜶(𝒌) = 𝜶𝟎𝒆𝒙𝒑(−𝒌/𝑻)
        
,where k is the current training epoch (starts withepoch 0), 𝜶𝟎 = 𝟎. 𝟖 , and T is the Total number of training epochs equal to 1000. Note that the epoch training involves all twenty four input samples for the 24 chosen colors to the network. Initial weights are randomized. The topological neighbourhood 𝑵𝒊,𝒋(𝒌) of node (j) around the winning unit (i) is given by
       
       𝑁i,j(𝑘) = exp(-dsquare i,j / 2𝜎square(𝑘))
Where

      𝜎(𝑘) = 𝜎0exp(−𝑘/𝑇)

And 𝑑i,j is the distance between the winning node i and surrounding node j.

a) Generate a figure of the original grid (random weights) followed by figures of the SOM after 20, 40, 100, 1000 epochs. Change the value of 𝜎0 = 1, 10, 30, 50, 70.

b) Conclusions are drawn on how the output changes with 𝜎0 and the number of epochs.

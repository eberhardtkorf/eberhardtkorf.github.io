# Percentage Drop vs. Needed Gain

### Background

Volatility in any investing market can cause a lot of fear and uncertainty regarding the underlying asset. The movement of prices is often measured on a percentage basis. For example if an asset that was worth $100 yesterday is worth $800 today we would say that the price and in turn the value of your investment fell by 20% because you only have 80% of $100 left. Some might believe that in order for your investment to go back to the value it was when the asset was worth $100 is just the inverse of the amount it dropped, in this case being a rise in 20%. However, this is not the case and a general formula to solve this problem will be developed here.

### Problem

We would like a formula that shows what is the needed gain for an investment to return to an original amount. For example if I lost 15% on my investment, what would be the percentage gain i need to return to the original value before the 15% loss. Thus, we have two variables namely the percentage drop and the percentage gain needed.

### Formulation

We can define the percentage drop as x and the percentage gain needed as y. If we imagine that we started with a $100 investment and our investment is now worth $80, meaning a 20% loss (x=0.2), we can set up a formula that will solve for y, the percentage our investment has to grow to return to $100:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;100%20%3D%20%281%2By%29%281-x%29%2A100" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;100%20%3D%20%281%2By%29%281-0.2%29%2A100" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;%5Cfrac%7B100%7D%7B80%7D%20%3D%20%281%2By%29" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;y%20%3D%200.25" title="equation" />
</p>

We can see that y is solved for as 0.25, meaning we need a 25% gain on $80 to return to our original investment value of $100. If we test this, 1.25*80 is indeed equal to 100. This result is interesting because it means percentage wise our investment has to gain more than it has dropped in order tojust return to what is was worth originally.

### General Formula

The starting euqation above can be simplified if we don't substitute in the value of x:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;100%20%3D%20%281%2By%29%281-x%29%2A100" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;1%20%3D%20%281%2By%29%281-x%29" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;%5Cfrac%7B1%7D%7B1-x%7D%20%3D%20%281%2By%29" title="equation" /><br>
    <img src="https://latex.codecogs.com/svg.latex?\Large&space;y%3D%5Cfrac%7B1%7D%7B1-x%7D-1" title="equation" /><br>
</p>

We see that we now have a general formula for this problem where y is our percentage drop and x is the percentage gain needed. This equation is an inverse rectangular gyperbola. This can be seen in the figure below:

<p align="center">
  <img src="https://raw.githubusercontent.com/eberhardtkorf/eberhardtkorf.github.io/main/pages/journal/entries/readmes/readme_images/inverse_hyperbola.png" />
</p>

Overall, we can see that the relationship between the drop of an investment and the needed gain for it to return to a pre-loss value is not linear. In fact, as the drop (x) becomes larger, the needed gain (y) grows in a exponential fashion with a drop close of 100% needing an infinite gain. A table showing this grwoth can be seen below:

| Drop (%) 	| Gain Needed (%) 	|
|----------	|-----------------	|
| 10       	| 11.11           	|
| 20       	| 25              	|
| 30       	| 42.86           	|
| 40       	| 66.67           	|
| 50       	| 100             	|
| 60       	| 150             	|
| 70       	| 233.33          	|
| 80       	| 400             	|
| 90       	| 900             	|





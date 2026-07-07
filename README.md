# makerfield_byelection_scale_scrollystory

This repository contains the building blocks of my story titled "How a few thousand voters chose Britain's next Prime Minister."

It is a visual explainer of how Andy Burnham could become PM with the backing of a tiny fraction of the U.K.'s electorate. 

The article follows a scrollytelling structure and is available at this link:
https://luciamack.github.io/makerfield_byelection_scale_scrollystory/

This repository contains the following files:


### index.html
The HTML, CSS, and JS code that creates the scrollytelling structure for the article.

It combines and adapts article templates made by Jonathan Soma and Aaron Reiss.

### images
This folder contains all the images used in the article.

Each grid was made on Adobe Illustrator before being exported as a PNG.

The design of these images and the article was inspired by a New York Times article from 2016 entitled "Only 9% of America Chose Trump and Clinton as the Nominees" (https://www.nytimes.com/interactive/2016/08/01/us/elections/nine-percent-of-america-selected-trump-and-clinton.html)

### visual_grid_calculations.csv
This file contains details on how I calculated the size of the various grids, and the sources for the statistics used in the article.

The grids used in the article are illustrative. Each square represents 5,000 people.

Where electoral data was not divisible by 5,000, rounding was used to determine the number of squares displayed. 

For the larger graphics, square roots were used to determine dimensions of the grids.

This means that rounding errors become larger as the graphics get larger. 

The biggest impact of this choice is that the amount of votes Andy Burnham received is actually slightly inflated when compared the size of the overall electorate.

The decision was made in the methodology to prioritize design and legibility over precision.  


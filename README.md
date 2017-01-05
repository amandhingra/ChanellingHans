# ChanellingHans
Hans Rosling is a data visualisation legend. 

His 2006 TED talk, The Best Stats You’ve Ever Seen, is one of the most viewed videos on the TED website  (http://bit.ly/2doLzAY). 

An interactive version of the GapMinder World visualisation used in that demo is available at 
www.gapminder.org/world (with a newer beta version at www.gapminder.org/tools). 

I have recreated the visualization using D3.js, JS, CSS and HTML.

To view the interactive visualization, a local server at least would be required and a JS enabled Internet Explorer.

Using the Gapminder_All_Time dataset provided along, the visualization package has the following features: 

1. D3.js, primitive JavaScript and CSS has been used in ChanellingHans.html file. The code is well commented and easy to understand.

2. The bubble plot that’s scaled to population values as radius and plotted against scaled values of GDP and LifeExp Appropriately. 
The GDP has been scaled with log values whereas the LifeExp and Population fields are scaled linearly for use. 
I have used appropriate Scaling variables to store the scale values and then called the variable to access the corresponding 
scaled values for data in the csv file. 

3. The Axes are properly labelled with well-defined ticks. The Fonts are used by referencing a css code at the beginning of the code file.
The class for text and axis lines has been referenced and the css code is used for styling. 
The CSS code also contains styling for buttons, sliders and legend attributes. 

4. Ordinal scaling has been used for mapping colors to regions from the data. 
Each region has been mapped to a Color using the “fill” variable. 

5. On accessing a particular country bubble in the middle of the code, one of the extra features that I have added is that the bubble 
on which the mouse pointer is will have precise markings on X and Y axes. This feature is basically in the Gapminder.org 
visualization but not on the requirements of this assignment. 

6. The slider can be changed manually using the mouse and the data of bubbles would be changed accordingly. 

7. Also, on clicking the icon of the legends, the data gets filtered by region. 
The play/pause/reset buttons can be then used to continue the animation. 

8. Clicking on any button or changing a slider or legend would pause the animation, which can then be resumed by the play button
or reset to initial settings by the reset button. The reset button can also be included in the set of extra features. 

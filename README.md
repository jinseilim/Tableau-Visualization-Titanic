# Tableau-Visualization-Titanic
Project 4: Visualizing Titanic Data in Tableau (Udacity Data Analyst Nanodegree)

## Links
First version: https://public.tableau.com/profile/jin.lim6189#!/vizhome/UdacityTitanicDraft/Story1
Final version: https://public.tableau.com/profile/jin.lim6189#!/vizhome/UdacityTitanicFinal/Story1

## Summary
- This project gives an overview of the demographics aboard the Titanic, and how various factors affected their survival when the ship sank. It draws conclusions about social class and gender, and ends with the assertion that being female and upper-class gave you the most chance of survival.

## Design
- Dash 1: Demographics of classes and their ports of embarkation. Here, I used a colored pie chart early so that viewers could quickly make the connection between each color and the social class. I reinforced that with a colored bar chart showing which port each class came from.
- Dash 2: Family members and loved ones. I used colored bar charts again to show which classes had the most loved ones onboard with them. Then, I used dark and light blue colors for the perished/survived bar chart to impress on viewers the difference between drowning (dark blue) and living (light blue).
- Dash 3: Age and survival. This follows the same design as the previous, with colored bars to denote which class had which spread of ages, as well as the survival rates across the board to try and uncover a correlation between age and survival.
- Dash 4: Gender and survival. This was an important and most robust finding of the visualization, so I made it large and put in icons.
- Dash 5: Class and survival. Again, with the light-blue and dark-blue colorings to tell the difference between dying and living.
- Dash 6: Gender, Class and Survival. The key finding of the visualization. I chose large bubbles so the viewer could really see the difference between those groups that tended to die and those that tended to survive. I thought the fact that you had to hover over the upper-class women’s “perished” bubble to see the tooltip enhanced rather than detracted from the visualization; it shows how few upper-class women really died in the sinking, that the bubble was too small to fit any text.

## Feedback
- I shared the visualization with a coworker. Here were her critiques:
- “It’s hard to tell which class is which.” I added large icons to the chart and made sure to choose a good color palette.
- “The dark-blue of the perished/survived plot looks too much like the lower-class graph”. I added perished/survived icons to firmly distinguish the plots, but kept the color scheme because I liked the dark-blue (drowning) and light-blue (just got wet) contrast, and thought it was good imagery.
- “The cabins and cabin survival plot is very hard to read, there’s too much red”. This was a mistake on my part. I had tried to include cabin data in my visualization, but in the end
there were too many missing values, thus creating the skewed plot. I deleted this dashboard from my story.
- “Some of the ending plots are just big shades of color, it’s very distracting and hard to distinguish”. I added icons to the final slides to more easily differentiate male/female.

## Resources
- Description of data and data obtained here: https://www.kaggle.com/c/titanic/data
- Icons from: https://www.flaticon.com/

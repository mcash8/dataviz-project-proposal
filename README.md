# Data Visualization Project

## Data

The data I propose to visualize for my project is the chess games dataset from: https://www.kaggle.com/datasets/datasnaek/chess and a sleep efficency dataset from: https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency 

## Prototypes

I’ve created a proof of concept visualization of the chess games dataset. It's a stacked bar plot and it shows the number of wins according to piece color and also how each game was won (ie: out of time, resign, check mate, or draw) 

[![image](https://user-images.githubusercontent.com/63068410/220152729-07241e1e-eac5-43be-80e2-1050dbc43901.png)
](https://vizhub.com/mcash8/294e9f53232746f1ac892105dc724be9)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 *  Is there an average win rate based on player ranking?
 *  Do both black and white pieces have an equal distrubution of wins?
 *  What opening moves are used the most?
 *  Is there a correlation between age and # of hours selpt?
 *  Are there any patterns with bedtime and deep sleep percentage?
 *  Task: Add a drop down menu for user selection of data to plot for sleep efficency dataset

## Sketches
 
![image](https://user-images.githubusercontent.com/63068410/220155332-c287ffc0-7fa4-4c22-beba-7a39cd0f85fd.png)

The purpose of the donut chart is to visualize the distribution of wins among the different piece colors. 

![image](https://user-images.githubusercontent.com/63068410/220155576-7fab3cd9-4506-4096-b8a7-2450a3a14305.png)

The second sketch would aid in answering the question: what opening moves are used the most? I think it would also be neat to add interactivity here and let the user select an opening move style and highlight the areas of the board corresponding to that move. 

![image](https://user-images.githubusercontent.com/63068410/220155643-dc18776d-fdcf-4c52-9faa-ed71897105f7.png)

The third sketch would aid in answering the question: What is the average win rate among different player rankings. In theory, the answer to this question should take on some distribution. This plot could also be interactive. 

![image](https://user-images.githubusercontent.com/63068410/220155687-04534372-e587-40d8-8379-d52b318b3217.png)

Finally, most of the sleep data can be visualized as a bar chart. For this, I plan make most of these graphs interactive and let the user choose the x/y data. 


## Milestones
Week 7 - Find a way to visualize a chess board in D3, begin heat map visual

Week 8 - Create a template bar chart for sleep data, create a template distribution plot for chess data

Week 9 - Implement drop down menu for graphics with visuals

Week 10 - Add labels, titles, legends to plots

Week 11 - Debug 

Week 12 - Debug

Week 13 - Debug, work on visusal aesthetics 

Week 14 - Finalize Visualization

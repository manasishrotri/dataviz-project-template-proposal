# Data Visualization Project

## Data
The data I have used for visualization in my project is COVID Cases data in May2020. 
The original data is taken from Kaggle: Corona virus cases. It has covid patient count, death counts reported all over the world. For the visualization purpose this data is filtered only for month of May.
This data is available on my gist [World corona virus cases May2020](https://gist.github.com/manasishrotri/4e43a48d4a8c89f011dbf18b7de28190)

## Step 1: Create prototypes and sketches of data to visualize

## 1.1 Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which countries were more affected worldwide?
 * In which countries patient count is decreasing and for which countries it is increasing?
 * Which continents have more variation in total cases
 * Which days had highest count of patient deaths
 * Display daywise spread countrywise


## 1.2 Prototypes

I’ve created a proof of concept visualization of this data. 
I have created a line chart of covid cases along Y axis and Date as X axis
With this screenshot, we can see new patient cases of United states are going down while for Brazil they are increasing

### Prototype graph 1

[![Covid_line_Chart](https://user-images.githubusercontent.com/60999947/94638694-8d1a3b80-02a8-11eb-9ab2-f65007c8fc2c.JPG)](https://vizhub.com/manasishrotri/2a52e358713f40af9002486d5e9ac6d3?edit=files&file=index.html&mode=full)

### Prototype graph 2

[![image](https://user-images.githubusercontent.com/60999947/94639494-4a596300-02aa-11eb-894d-b36e772b6718.png)](https://vizhub.com/manasishrotri/80b2816144f74b90a29d6a17801d48c7)

 
 
## 1.3 Sketches

<img width="1394" alt="Sketch_Covid_Data_may" src="https://user-images.githubusercontent.com/60999947/94639033-47aa3e00-02a9-11eb-99c8-d2e09221c4be.png">

* Graph1 is line chart showing Total cases in a month of May. This answers two questions, 
   Which countries were more affected worldwide?
   In which countries patient count is decreasing and for which countries it is increasing?
* Graph 2 is box plot of Total cases showing variation and median of in total cases in a month for all countries.
* Graph 3 is bar chart for comapring spread of virus on 1st day and on 31 st day
* Graph 4 is bubble chart which shows country wise data


## 1.4 Schedule of Deliverables

[done] Week 1:
* Read data using D3 and react 
* Plot line graph

[done] Week 2: 
* Prepare data for Box plot
* Understand how to create world map with size of data as bubbles

[done] Week 3: 
* Complete box plot
* Add iteraction for line chart as drop down option for countries

[done] Week 4:
* Work on World map
* Create bar chart with React &  D3

[done] Week 5:
* Complete world chart 
* Complete project report


## Step 2: Interactions in visualization

* For line chart, when mouse hover over a country name, the line for that country is highlighted
* Box plot, when hovered over box, shows values quantile 1, median and quantile 3
* World map shows country name and count of cases on 31st May on hovering over that country 

## Step 3: Final Visualization


## Future Work
* Create animated world chart(or slider over day), which changes values daywise cases
* Create React app

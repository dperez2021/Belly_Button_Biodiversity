# Belly Button Biodiversity

## Background

In this assignment, we will use plotly graphs to build an interactive dashboard using the Belly Button Biodiversity dataset.

The dataset reveals that a their are some microbial speciest (also known as operational taxonomic unit, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Part 1: Plotly Bar & Scattplot graphs

In order to prepare the plotly bar and scattplot graphs we used the D3 library to read in samples.json. 

Next, we create a horizontal bar chart with a dropdown menu to display the top 10 OTU's found in that individual.

![Top_10_Bar_Chart](https://user-images.githubusercontent.com/88256967/140659500-e8744e4c-674a-4063-8460-0e0bd99785c9.PNG)


Then, we create a bubble chart that displays each sample. This will display the sample metadata including an individual's demographic information.

![OTU_BACTERIA_BUBBLE_CHART](https://user-images.githubusercontent.com/88256967/140659502-27d20ac9-d8c7-48b6-ae8d-01702570e69c.PNG)


## Part 2: Plotly Gauge Chart

The opportunity to present a gauge chart is for better visualization. Therefore, we adap the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual. We will modify the code to account for values ranging from 0 through 9.

![Gauge_StyleChange](https://user-images.githubusercontent.com/88256967/140659491-2b4dda3c-c35f-4da8-abc1-06b227e77fbb.PNG)


## Results

The dashboard is located at https://dperez2021.github.io/Belly_Button_Biodiversity/

![Site_Screenshot](https://user-images.githubusercontent.com/88256967/140659496-4fd12ac8-afc1-4c6e-80c4-d6981dbbad96.PNG)


# Module13-Challenge-from-Bacteria-to-Beef
## Overview
Volunteers participated in a study by twirling a sterile swab in their belly buttons to collect their microbes. The purpose of this project is to create a dynamic webpage where the volunteers should be able to identify the top 10 bacterial species in their belly buttons.

This project consists of four technical analysis deliverables:

- Horizontal Bar Chart
- Bubble Chart
- Gauge Chart
- Customized Dashboard

Technologies used for the deliverables are HTML, CSS, JavaScript, Plotly, and D3.js

## Results

### Horzontal Bar Chart
A horizontal bar chart was created to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. 

The horizontal bar chart displays the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.

![image](https://user-images.githubusercontent.com/31812730/203476918-c3821e60-380c-438b-b698-a6a73472fd40.png)

### Bubble Chart
A bubble chart was created to display the following information when an individual’s ID is selected from the dropdown menu webpage:
- otu_ids as the x-axis values
- sample_values as the y-axis values
- sample_values as the marker size
- otu_ids as the marker colors
- otu_labels as the hover-text values

![image](https://user-images.githubusercontent.com/31812730/203478653-ffe5d88c-23ee-41f9-8053-21962d952ada.png)

### Gauge Chart
A gauge chart was created to displays the weekly washing frequency, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

![image](https://user-images.githubusercontent.com/31812730/203479593-f6dca456-35a7-4b60-b301-83a9641cc71a.png)

### Dashboard
A dashboard was created adding all the charts in one page.

When the webpage loads for the first time, with the bar chart, the bubble chart, and the gauge chart, the dashboard looks as the image shown below:

![image](https://user-images.githubusercontent.com/31812730/203480671-8a52bfb6-4749-4db6-8129-fa838a1c43e7.png)

### Customize the Dashboard
HTML and Bootstrap were used to customize the webpage for the dashboard.

Following customization was done:
- An image added to the jumbotron
- Background color added to the webpage
- Custom font was used with contrast for the colors
- Navigation bar added that allows user to select only the bar, or the bubble, or the gauge chart on the page.

Customized dashboard has following elements is shown in the image below:
- Dropdown to examine data from each individual
- Bar chart featuring the top ten microbial species (OTUs or operational taxonomic units)
- Bubble chart featuring all microbial species
- Gauge of the frequency of belly button washes weekly for each individual

![image](https://user-images.githubusercontent.com/31812730/203481978-e63c2454-8a1b-4900-bd35-9b674c325766.png)

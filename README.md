# belly-button-challenge
Belly Button Dataset

In this activity, I successfully built an interactive dashboard that explores the Belly Button Biodiversity dataset which catalogs the microbes that colonize human navels. Can you believe our navels have these microbes present?

The dataset revealed that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
<p align='center'> <img src='/images/Bellybutton Biodiversity Dash'></p>

#Steps
1. I created a new repository for this project called "belly-button-challenge"

2. Once the Git repository was cloned, I read in  the D3 library to read in samples.json from the URL (https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json)

3. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    - Using sample_values as the values for the bar chart.

    - Using otu_ids as the labels for the bar chart.

    - Using otu_labels as the hovertext for the chart.
    
4. Created a bubble chart that displays each sample.

    - Using otu_ids for the x values.

    - Using sample_values for the y values.

    - Using sample_values for the marker size.
    
    - Use otu_ids for the marker colors.
    
    - Use otu_labels for the text values.
    
5. Displayed the sample metadata, i.e., an individual's demographic information.

6. Displayed each key-value pair from the metadata JSON object somewhere on the page.

7. Updated all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.

8. ##Last Step##: Deployed the app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file











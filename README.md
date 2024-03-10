## Integrated project: Understanding and trusting data (Part 2)
© ExploreAI Academy

In this notebook, we're going to dive into the agricultural dataset to find patterns and try to get insights. We're also stopping for a moment to make sure our data are true and sound by validating it against other data sources. 

⚠️ **Note that this notebook guides us through the activities we need to complete in order to complete the MCQ. There will be 10 MCQs based on the analysis we complete, code we write, visuals we create, and insights we gain.** 

We could be asked to create code, modify code, or interpret some of the results, so we should take our time to do the analysis...

### Instructions

- Complete each step of the analysis.
- Make notes after each output. Try to think about what the numbers say and what it means. 
- Explore the data fully, using all the tools we have learned so far.
- Collaborate with your peers by discussing your insights and sharing your solutions. When it comes to the MCQ, be ready to take it on on your own!

### MCQ checklist: 
- Ensure you have completed all code cells.
- Make sure that you looked at and understood all outputs we discussed today.
- Make sure you completed a crop-by-crop analysis of the data.
- Make sure you took the time to get to know the dataset well.
- Make sure you made thorough notes for each output.

### What to expect in the MCQ
- Questions on interpreting visuals.
- Questions on interpreting data.
- Questions to modify code and discuss/interpret data.
- Questions on how to create visuals or perform analysis.

# Introduction

Fantastic progress so far! Now, let's roll up our sleeves and delve into the heart of our Maji Ndogo project – the exploratory data analysis (EDA) and visualisation. This phase is where our detective hats come on. We're going to sift through our dataset, turning numbers and stats into insightful, visual stories.

Seaborn, our trusty Python visualisation library, will be our main tool here. Think of it as our magnifying glass, helping us zoom in on the nuances of our data. We'll create plots that show relationships between variables like rainfall, pH levels, and temperature. Scatter plots, line graphs, heatmaps – you name it, we'll be creating it. This isn't just about making pretty graphs; it’s about unearthing the hidden patterns and correlations that are key to our agricultural decisions.

But wait, there's a critical step we can't overlook – validating our data. You see, our fields' data need a reality check. We'll be pulling in weather data from nearby stations to compare with our farm measurements. If the temperature, pH, and rainfall data from our farms align closely with these weather stations, we're on the right track. This isn't just about data integrity; it's about ensuring our data reflects the true environmental conditions of Maji Ndogo before we make conclusions or explore the data with AI.

Here’s the task at hand: We'll use weather data from five stations across Maji Ndogo. Each field in our dataset is close to one of these stations, so we also have some data connecting each field in our dataset to the correct weather station. Our goal? To compare and validate key climate measurements. By confirming the accuracy of our data, we increase our confidence in the decisions we make next.

This part of the journey is crucial. We're laying down a solid, trustworthy foundation for our project. Your keen eye for detail and analytical prowess will be invaluable here. Ready to dive into the depths of data validation and visual storytelling? Let's uncover the truths hidden in our numbers and bring precision to our farming strategies in Maji Ndogo.

Onwards and upwards – let's make our data work for us and bring this vision to life!

Saana
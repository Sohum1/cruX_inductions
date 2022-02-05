# Python Simulation for Effective Covid-19 Strategy

This is an agent based simulation of virus spread across a population. The effects of different measures to stop the spread, like masks, lockdowns, and vaccines are also simulated. This project visualises the effects that various measures have on how diseases spread and gives an idea about the most effective methods of tackling the disease.

As an extension to the project, I ran a sentiment analysis test on tweets scraped from Twitter to gauge the sentiment of the general public towards wearing masks.

## Dependencies:

'animation_data.csv'

'tweet_ranges.csv'

## Notes about the dependencies:

### Simulation

One run of the notebook 'Pandemic_Simulation_in.ipynb' represents one pandemic breakout in a virtual population (the results of which can be seen in the first graph of the 5th section of the notebook). Therefore, to compare the efficacy of multiple measures together, I ran the simulation multiple times with different initial conditions (percent of population wearing masks, lockdown intensities, and vaccination rates) with a starting population of 10,000 people and compiled the data generated by the simulation in a csv file named 'animation_data.csv'. 

To run the rest of the section 5, which creates all graphs comparing the different measures of stopping virus spread, the 'animation_data.csv' csv file will have to be downloaded from this repository.

### Sentiment Analysis

The Python script that runs sentiment analysis on the tweets (gathered as mentioned above and in the notebook) does not run in this notebook, as the file it reads the tweets from is too large to be included in the repository. The script generates a different csv file named 'tweet_ranges.csv' which is required to create the graph made in section 6 of the notebook and can be found in this repository too. This script running sentiment analysis is demonstrated in section 6 inside triple quotations. The command used to scrape the tweets is also mentioned. 

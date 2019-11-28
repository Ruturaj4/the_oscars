The Oscars
==============================

Great stories and great visual effects

Author: Ruturaj Kiran Vaidya

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting

--------



<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

### Before Getting Stated

If you are only interested in looking at the notebook then go to (There are notebook rendering problems in github ecosystem):

https://nbviewer.jupyter.org/github/Ruturaj4/the_oscars/blob/master/notebooks/1.0-rkv-the-oscars.ipynb

All the graphs are plotted using `matplotlib` and `plotly`.

### Aim

<ul>
<li>Load the dataset and see how storytelling and visualization help describing the dataset and finding additional feature </li>
<li>Build 3 or more visualizations</li>
</ul>

### Dataset

I selected the soccer dataset used in previous projects, as it has a lot of features to work with and it will be great for visualizations.

Dataset: https://github.com/fivethirtyeight/data/tree/master/soccer-spi

Specific Dataset Link: https://projects.fivethirtyeight.com/soccer-api/club/spi_matches.csv

### Discussion

#### Unique Idea (apart from project aim) : In addition to what has been instructed, I decided to use two different visualization libraries - "matplotlib and plotly" - to test their graphs, code in general. Also it's so much fun!

First, I decided to go with the soccer dataset, because I thaught that it would be very great for visualizations and as I am a big football (soccer) fan, I thaught that it would a fun personal project. After selecting the dataset, I decided to work on specific features and ignore others. I also decided to visualize using a couple of libraries - so that I can compare the visualization and code required to plot. I used matplotlib and plotly to visualize. Following are some of the visualizations:

Plotted using `matplotlib`:

![alt text](/reports/figures/tot_teams.png)
![alt text](/reports/figures/tot_matches.png)

Plotted using `plotly`:

![alt text](/reports/figures/goals.png)

While, plotting these - I thought of looking at home and away win percentage, i.e. if it really matters whether you play at home or at away ground. From following plot, it seems that it does matter (at certain percentage), although it is not totally impossible to win if playing away.

Plotted using `plotly`:

![alt text](/reports/figures/home_away.png)

By comparing two different visualization libraries, I observed that plotly does give better results with less (or rather simple) code.

### References

I got some of the ideas from following post:

<ul>
<li>Kaggle data anlysis: https://www.kaggle.com/pavanraj159/european-football-data-analysis/notebook</li>
</ul>

### License

<b>MIT</b>

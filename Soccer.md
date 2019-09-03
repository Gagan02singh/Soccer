# Soccer Statistics

### Install
This project requires the following Python libraries installed:

* [NumPy](www.numpy.org)
* [Pandas](pandas.pydata.org)
* [matplotlib](matplotlib.org)
* [scikit-learn](scikit-learn.org/stable/)
* [calender]()
* [matplotlib]()


You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Run
In a terminal or command window, navigate to the top-level project directory `Soccer/` (that contains this README) and run one of the following commands:
> ipython notebook Soccer.ipynb

or

> jupyter notebook Soccer.ipynb

This will open the Jupyter Notebook software and project file in your browser.

### Data

This dataset includes 39,669 results of international football matches starting from the very first official match in 1972 up to 2018. The matches range from FIFA World Cup to FIFI Wild Cup to regular friendly matches. The matches are strictly men's full internationals and the data does not include Olympic Games or matches where at least one of the teams was the nation's B-team, U-23 or a league select team.

##### Features
- **date** - date of the match
- **home_team** - the name of the home team
- **away_team** - the name of the away team
- **home_score** - full-time home team score including extra time, not including penalty-shootouts
- **away_score** - full-time away team score including extra time, not including penalty-shootouts
- **tournament** - the name of the tournament
- **city** - the name of the city/town/administrative unit where the match was played
- **country** - the name of the country where the match was played
- **neutral** - TRUE/FALSE column indicating whether the match was played at a neutral venue

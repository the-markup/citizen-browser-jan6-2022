# Citizen Browser - One Year after the Capitol Riot on Facebook
This repository contains code to reproduce the findings featured in our story: "[One Year After the Capitol Riot, Americans Still See Two Very Different Facebooks](https://themarkup.org/citizen-browser/2021/01/14/biden-and-trump-voters-were-exposed-to-radically-different-coverage-of-the-capitol-riot-on-facebook)" from our series [Citizen Browser](https://themarkup.org/series/citizen-browser/).

Our methodology is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)."

## Data files

`data/biden.csv`
This CSV file contains the unique links shown to Citizen Browser panelists who reported voting for Joseph Biden in the 2020 U.S. general election, along with a count of the number of panelists who were shown the link.

`data/trump.csv`
This CSV file contains the unique links shown to Citizen Browser panelists who reported voting for Donald Trump in the 2020 U.S. general election, along with a count of the number of panelists who were shown the link.


## Query parameters

### Time Frame
Our query requested data observed between **Dec. 30, 2021**, and **Jan. 5, 2022**.

### Demographics
We filtered the data to only include observations from Citizen Browser panelists who reported voting for Joseph Biden or Donald Trump in the 2020 U.S. general election.

### Keywords
We performed a keyword search for the following terms: 
`"capitol", "jan. 6", "january 6"`

We looked for these terms in Facebook posts, link URLs, and the poster's account name and page address.

### Exclusions
We excluded any posts flagged as sponsored, any posts that were clearly advertisements, and any links that were not associated with the activity surrounding the riot. 

We excluded any posts made by Facebook itself.

We excluded links from any domain that had only one link served in our dataset. 
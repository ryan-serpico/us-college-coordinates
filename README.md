![U.S. College Coordinates repo banner](./img/us-college-coordinates-banner.png)

**Tl;DR:** This repo hosts a spreadsheet of U.S. college and university coordinates. [You can view and download it here](https://flatgithub.com/ryan-serpico/us-college-coordinates/blob/main/output/college_coordinates.csv?filename=output%2Fcollege_coordinates.csv&sha=42aab6b20d8afd59755699bfc036099fad6a9b97).

Several months ago I was working on a project that required a list of Texas college and university coordinates. I couldn't find this data anywhere online, so I resorted to copy/pasting coordinates out of Google Maps. Not fun.

Turns out I didn't need to do that. 

The U.S. Department of Education keeps tabs on the coordinates of every college and university in the country through the [Integrated Postsecondary Education Data System (IPEDS)](https://nces.ed.gov/ipeds/). I found the data in [the College Scorecard dataset](https://collegescorecard.ed.gov) the DOE also maintains. It's a beast of a dataset weighing in at 221.2 MB. It's probably too large for the average journalist just trying to get coordinates for a story. A cursory web search turned up no results when I saught a slimmed down version of the data — so I made one myself.

I pulled the data on *March 16, 2023*. 6,681 colleges and universities are included in the dataset — both public and private. 

You can find the data in the `output` folder. You can also view it first in the flatgithub viewer [here](https://flatgithub.com/ryan-serpico/us-college-coordinates/blob/main/output/college_coordinates.csv?filename=output%2Fcollege_coordinates.csv&sha=42aab6b20d8afd59755699bfc036099fad6a9b97).

If this data helps you out with a project, please let me know! I'd love to hear about it. Reach out to me on social media.

## How to replicate

If you'd like to run the code yourself (maybe there's more recent data that's come out), use the following steps:

1. Clone the repo.
2. Install the requirements with `pip install -r requirements.txt`.
3. You can either run the jupyter notebook or use the `nbexec get-coordinates.ipynb` to run it as a script.

# assignment-2
This repository contains data, analytic code, and findings that support portions of the article, “Republican Candidate Leads In Donation for Northeast Queens City Council Race,” published April 18, 2025. Please read that article, which contains important context and details, before proceeding.

Data
This analysis uses spreadsheets.

The spreadsheets come from the following sources:

Name of source:
name_of_spreadsheet.xlsx: Raw data of New York City Campaign Finance Board contribution data for City Council District 19 race.
Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

RECIPNAME — Candidate's name who received the donation
AMNT — The amount donated to each campaign
CITY — Where those who donated to the campaign were from

Methodology
The notebook DDT-Lam-Assignment-2.ipynb performs the following analyses:

Part 1: Number of donations made to each candidate
I queried the data to find out how often the RECIPNAME showed up in the data, which I used to find out how many seperate donations had been made to each candidate
Part 2: Amount of donations made by each candidate
I summed up the amount ("AMNT") made to each candidate to see how much they had made in total
Part 3: Who and where were donations made
I then groupedby the name ("NAME") of each candidate as well as–seperately–the city ("CITY") where donations were made, in reference to each candidate.

Outputs
The notebooks output this spreadsheet which is found at the bottom of the notebook.

Running the analysis yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3
The Python libraries specified in requirements.txt
Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?
Contact YOUR NAME HERE at david.deturris98@journalism.cuny.edu.

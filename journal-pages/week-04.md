---
layout: default
---

# Week 04

[← Back to Home](../index.md)

# Experiment 4 

# Week 4 - Artificial Intelligence


## In class activities


## Independant Study: AI-Assisted Data Exploration

Overview

Choose a public dataset about life in Aotearoa New Zealand and use cloud-based AI tools to explore, interpret, and represent the data. The challenge is to go beyond a single prompt, working through sustained dialogue with the AI, directing its decisions, and critically evaluating its outputs.


### Step 1: Find a Dataset

*Browse the open data catalogue at catalogue.data.govt.nzLinks to an external site. and find a dataset that interests you. Look for something with a downloadable CSV file that is small enough to upload into a cloud AI tool (aim for under 10MB, or a few thousand rows).*

*Choose something you find genuinely interesting. The data should relate to a real aspect of life in Aotearoa that you would want to explore further.*

When collecting data from the data.govt website, I decided to search using some keywords. I searched things such as, 'kiwi', 'traffic', 'fish', and 'weather'. I decided upon using historical livestock data. These statistics were initially interest as I felt that was industry was so important to New Zealand.


### Step 2: Understand the Data

*Upload your CSV into a cloud AI tool (e.g. CoPilot, Gemini, NotebookLM, ChatGPT) and have a conversation about it. Ask the AI to explain what is in the dataset: what the columns mean, what the values represent, how much data there is, and what is missing or incomplete.*

I decided to input this data into NotebookLM & Gemini.

This was the exact response given by Gemini.

"Column Descriptions
geography_type: Categorizes the scale of the region. It includes four levels: New Zealand (national), Island, Region, and Territorial Authority.

geography_name: The specific name of the geographic area (e.g., North Island, Auckland Region, or specific districts).

year: The calendar year the data was recorded (ranging from 1971 to 2017).

animal: The type of livestock recorded. There are 5 categories: Beef cattle, Dairy cattle, Deer, Sheep, and Total cattle.

count: The numerical population of the specific animal type in that region and year.

Data Volume
Total Rows: 4,240

Total Columns: 5

Time Span: 47 years (1971–2017)

Unique Locations: 82 different geographic names.

Missing or Incomplete Data
The dataset contains 530 missing values, all of which are in the count column.

Year-specific gaps: The years 1997, 1998, 2000, and 2001 have the highest number of missing values (90 missing counts each), suggesting that certain livestock surveys were not conducted or recorded for these years across most regions.

Animal-specific gaps: Deer has the most missing values (145), followed by Dairy cattle (108).

Geography-specific gaps: The Region category has the most missing data (368 records), while New Zealand (national level) only has 28 missing records.

All other columns (geography_type, geography_name, year, and animal) are fully populated for all 4,240 rows."

*Consider:*
*What stories might this data contain?*
*What questions could it answer?*
*What biases or gaps are present?*
*Who collected this data, and for what purpose?*


### Step 3: Design Multiple Representations

Ask the AI to produce a visualisation of the data, but don't accept the first output. Direct the AI: specify the form, the visual encoding, the audience, the story you want to tell. Iterate through at least three distinctly different representations of the same data. These could be code-based (e.g. p5.js or HTML), textual, visual, or even prompts for physical/analogue translations.

For each version, make deliberate design decisions about what to change. You might vary the format (chart, map, interactive page, narrative text), the visual encoding (colour, size, position, shape), or what subset of the data to foreground.


### Step 4: Critically Evaluate

Look at the representations you've produced and reflect on the AI's design choices:

What did the AI default to? (e.g. bar charts, blue colour schemes, generic titles)

What did you have to override or redirect?

What assumptions did the AI make about the data or the audience?

Which representation is the most interesting, and why?

What would you do differently if you were building this without AI?

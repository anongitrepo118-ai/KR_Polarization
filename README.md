# Code for Anonymous ICWSM Submission

This repository contains the analysis code associated with the submitted manuscript.

## Repository Structure

The analysis is organized into six Jupyter notebooks:

- `01_politicians_youtube.ipynb`  
  Processes and analyzes comments associated with politicians on YouTube.

- `02_politicians_instagram.ipynb`  
  Processes and analyzes comments associated with politicians on Instagram.

- `03_youtubers_youtube.ipynb`  
  Processes and analyzes comments associated with political YouTubers on YouTube.

- `04_youtubers_instagram.ipynb`  
  Processes and analyzes comments associated with political YouTubers on Instagram.

- `05_combine_and_compare.ipynb`  
  Combines the four datasets and conducts the cross-platform and cross-producer comparisons reported in the manuscript.

- `06_sensitivity_check.ipynb`  
  Conducts sensitivity analyses to evaluate the robustness of the main findings.

## Data

The study uses public comments collected from YouTube and Instagram.

The raw datasets are not included in this repository.

## Running the Analysis

The notebooks are numbered according to the intended workflow. Run them in the following order:

1. `01_politicians_youtube.ipynb`
2. `02_politicians_instagram.ipynb`
3. `03_youtubers_youtube.ipynb`
4. `04_youtubers_instagram.ipynb`
5. `05_combine_and_compare.ipynb`
6. `06_sensitivity_check.ipynb`

The first four notebooks process the four platform–producer combinations separately. The fifth notebook combines the resulting data and performs the main comparative analyses. The final notebook performs sensitivity checks.

## Requirements

The analyses were conducted in Python using Jupyter notebooks.

Because the raw social-media data are not distributed with this repository, complete reproduction of the analyses requires access to the underlying datasets.

## Anonymous Review

This repository has been prepared for anonymous peer review. Identifying information has been removed.

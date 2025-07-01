# Word Embedding Strategic Positioning (WEB) Scores for U.S. House Candidates (2018-2022)

## Overview
This dataset contains positioning estimates (WEB Scores) for candidates running for the U.S. House of Representatives from 2018 to 2022. WEB Scores are estimated using candidates' campaign website issue statements ([CampaignView](https://campaignview.org/)). A description of the methodology and scores can be found [here](https://www.colinrcase.com/files/case_measuringpositioning.pdf). The dataset contains the following variables:
- candidate_webname: the candidate's name, standardized across years
- state_postal: the candidate's state postal abbreviation
- cd: the candidate's congressional district
- cand_party: the candidate's party
- year: the year of the election
- web_score: the candidates's WEB Score (NA if candidate did not have a website issue page)
- FECCandID: identifier produced by the Federal Election Commission for candidates who file with the FEC
- bioguide_id: identifier from Congress.gov for candidates elected to Congress

## Citation
Users of the dataset should cite the corresponding article:

> Case, Colin R.. "Measuring Strategic Positioning in Congressional Elections." _Journal of Politics._ (Conditionally Accepted).

## Download
The dataset in CSV format is available [here](https://github.com/crcase/WEB-Scores/blob/main/webscores2018-2022.csv) (last updated on July 1, 2025) by clicking "download raw file" in the upper right hand corner.


## Unicorn Companies Data Analysis

This project focuses on analyzing historical data of "unicorn" companies—startups that have reached a valuation of $1 billion or more. Developed to assist an investment firm specializing in high-growth companies, this project extracts actionable market insights regarding industry valuations and the speed at which these dominant companies emerge.
The findings aim to provide a competitive edge in recognizing market trends and optimizing strategic asset allocation.

## Objectives

* Industry Trajectory: Pinpoint which sectors yield the highest market valuations.
* Growth Velocity: Measure the average time it takes for startups to scale into unicorns.
* Geographical Hotspots: Map out where high-growth companies are clustering globally.
* Investor Impact: Evaluate how backing from premier investors correlates with multi-billion dollar valuations.

## Data Dictionary
The project relies on the unicorns database, which structures operational, geographical, and financial data across four core tables:
## dates Table

| Column | Type | Description |
|---|---|---|
| company_id | Key | A unique ID for the company. |
| date_joined | Date | The date the company officially became a unicorn. |
| year_founded | Integer | The year the company was originally founded. |

## funding Table

| Column | Type | Description |
|---|---|---|
| company_id | Key | A unique ID for the company. |
| valuation | Numeric | Company valuation in US dollars. |
| funding | Numeric | The amount of funding raised in US dollars. |
| select_investors | Text | A list of key investors in the company. |

## industries Table

| Column | Type | Description |
|---|---|---|
| company_id | Key | A unique ID for the company. |
| industry | Text | The industry that the company operates in. |

## companies Table

| Column | Type | Description |
|---|---|---|
| company_id | Key | A unique ID for the company. |
| company | Text | The name of the company. |
| city | Text | The city where the company is headquartered. |
| country | Text | The country where the company is headquartered. |
| continent | Text | The continent where the company is headquartered. |



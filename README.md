# Census Data Analysis Project
## Overview

This project presents a comprehensive analysis of census data from a modestly sized town situated between two major cities. The analysis was conducted to support policy development, infrastructure planning, and informed decision-making—particularly regarding what the local government should build on an unoccupied plot of land.

To ensure reliable insights and avoid biased or misleading conclusions, the dataset went through extensive data cleaning, followed by exploratory data analysis (EDA), descriptive statistics, and multiple visualisations.

## Project Objectives

Clean and preprocess the census dataset to correct errors, inconsistencies, and missing values.

Analyse demographic characteristics such as:

Population distribution

Employment trends

Birth and death rates

Migration patterns

Marital status

Religion affiliation

Household occupancy

Provide data-driven recommendations to guide future development projects.

## Data Cleaning Summary
#### Duplicate Records

Identified and removed duplicated row 7729.

#### Age Column

Converted age values from float to integer for demographic accuracy.

#### Relationship to Head of House

Replaced missing values with appropriate categories after investigation.

Corrected misspellings (e.g., “Neice” → “Niece”).

Removed an invalid household involving underage marriage.

#### Marital Status

Investigated missing values and updated based on:

UK Marriage Act 1949

Marriage & Civil Partnership (Minimum Age) Act 2022

Imputed:

Students → Young Adult

Children → Minor

#### Gender

Imputed missing entries based on household composition.

#### Occupation

Regrouped many unique occupations into broader categories for clearer analysis.

#### Infirmity

Missing values imputed as None.

#### Religion

Unrecognised entries (e.g., Jedi, Sith) → None

“Undecided” → Not Given

NaN values → Not Given (mostly minors/young adults)

## Key Demographic Findings
## Population Structure

Dominated by middle-aged adults (35–44).

Depressed 0–4 age group suggests a low birth rate.

Population appears healthy and growing.

## Employment & Unemployment

Age 35–39 has the highest unemployment.

Female unemployment is generally higher than male.

Employment distribution:

53.6% Employed

19.9% Students

7.7% Retired

6.6% University Students

6.1% Unemployed

5.9% Children

## Marital Patterns

Marriage rate ≈ 350 per 1000

Divorce rate ≈ 86 per 1000

Females show a higher divorce rate than males.

## Religion Affiliation

None: 34.2%

Not Given: 25.1%

Christian: 21.1%

Catholic: 10.8%

Not enough demand to justify constructing another church.

## Household Occupancy

Most homes have 1–5 occupants.

Mode: 2-person households.

High-density housing is not required.

## Commuter Analysis

Two types of commuters identified:

1. By Occupation

Includes:

Researchers

Scientists

Journalists

Lecturers

Education officers

Lab technicians

Librarians

Total: 1,025

2. By Religion

Members commuting to places of worship in nearby cities:

Christian

Muslim

Sikh

Jewish

Methodist

Agnostic

Bahai

Total: 3,023

## Total Commuters: 4,048 (40.02%)

A large proportion of the population travel outside the town daily.

## Birth & Death Rates

Crude Birth Rate: ~10.78 births per 1000

Crude Death Rate: ~2.8 deaths per 1000

Indicates low mortality and a generally healthy community.

## Migration Analysis

Immigrants: 1,435

Emigrants: 1,337

Net Migration Rate: 9.69 (positive)

The town is growing and attracting more residents—requiring investment in future infrastructure.

## Recommendations
#### Build a Train Station

High commuter rate (40%) indicates strong need.
A train station would:

Reduce road congestion

Improve city connectivity

Support economic mobility

#### Do NOT Build High-Density Housing

Occupancy levels do not justify it.

#### Expand Infrastructure

The town is receiving positive net migration and needs more future-proof systems.

#### Additional Religion Buildings NOT Needed

Most people have no religious affiliation.

#### Maintain Current Schooling Facilities

School-age population is stable.

#### Plan for Elderly Care Services

Middle-aged residents will transition to older age groups in coming years.

## Tools 

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook
## References

BBC (2016). Jedi is not a religion, Charity Commission rules.

GOV.UK. Marriage Act 1949.

UK Ministry of Justice. Marriage & Civil Partnership (Minimum Age) Act 2022.

UNCRC. Children’s Human Rights, Article 14.

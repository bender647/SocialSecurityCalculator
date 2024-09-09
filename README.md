# SocialSecurityCalculator
Python script to calculate estimated Social Security Benefits


 This Python script will calculate your expected retirement benefits
 from Social Security given your annual earnings. This script does
 not extrapolate potential future earnings. It only uses the income
 information provided into the EarningsRecord dictionary below.

 Inputs:
 
1) EarningsRecord -
Dictionary mapping a year to the amount of Social Security eligible earnings in that particular year.  Fill this out with estimated data as far as possible, preferably through your last year of contributions.

2) NationalAverageWageIndexSeries -
Data pulled directly from the Social Security website for the national average wage data

3) retire_year -
The year you reach full retirement age of 67 (this is not necessarily the year you intend to stop contributing).

These inputs may be coded into the script, or provided in an included Python file named mydata.py

 Written by Ryan Antkowiak 2017-07-15
 Copyright (c) 2017 All Rights Reserved

 Updated by Kevin Fowlks (fowlk1kd@gmail.com) 2019-09-03

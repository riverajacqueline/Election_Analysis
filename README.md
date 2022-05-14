# Election Analysis

## Overview of Election Audit
The Colorado Board of Elections requested an audit for the tabulated results for the U.S. Congressional precinct.

### Purpose
The purpose of this elections audit was to collect:
- the total votes cast
- the total number of votes for each candidate
- the total percentage of votes for each candidate
- the winning candidate based on popular vote
- the voter turnout for each county
- the percentage of votes from each county out of the total count
- the county with the highest voter turnout

## Election Audit Results

- **How many votes were cast in this congressional election?**

Using the code below, the outcome of the total number of votes cast in the congressional election was able to be determined.

![image](https://user-images.githubusercontent.com/103764279/168446377-f664068e-bd96-42b2-9519-4173621f430b.png)

![image](https://user-images.githubusercontent.com/103764279/168446408-7fc75eae-7ac7-4fe3-bf39-c83bb270c03d.png)

- **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**

Using a for loop, the number of votes and the percentage of total votes was able to be determined for each county in the precinct.

![image](https://user-images.githubusercontent.com/103764279/168446601-68c4389b-35be-420e-a4f2-15a591bd776d.png)

![image](https://user-images.githubusercontent.com/103764279/168446558-edc3c259-ba41-4a82-86d1-eced0266ddf6.png)

- **Which county had the largest number of votes?**

According to the election results of the audit, it can be concluded that Denver County acquired the largest number of votes.

![image](https://user-images.githubusercontent.com/103764279/168446794-559c2738-f825-45bc-b911-9d4d85dc1630.png)

![image](https://user-images.githubusercontent.com/103764279/168446732-9dba7eb9-7b2f-416f-b5ef-c0daa8640aff.png)

- **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

By iterating through a for loop, the code below is able to provide the breakdown of the number of votes and the percentage of votes for each candidate.

![image](https://user-images.githubusercontent.com/103764279/168447003-c5066f0b-e042-453f-adb7-4324dbb3e93c.png)

![image](https://user-images.githubusercontent.com/103764279/168446862-4c21081a-0289-49c0-825d-983eb0031e0a.png)

- **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**

Using an if statement within our for loop allows a condition to be set in order to find the winner of the election based on the highest vote count and highest percentage of votes.

![image](https://user-images.githubusercontent.com/103764279/168446983-392faa6a-d295-4dc6-8297-223735205fc9.png)

![image](https://user-images.githubusercontent.com/103764279/168446966-a0b1dff8-5d4b-46a0-9b57-6d0123abf431.png)


## Election Audit Summary

This script was designed to be able to gather and caclutate election results quickly. It can be used to audit other elections as well by modifying the candidate names and counties based on the csv being worked from. 

In the script, election results were able to show the total number of votes per county and the total number of votes each candidate received. To further analyze the data, the script could be modified to show the number of votes each candidate received per county.

Given there was more information on the csv, there could be a deeper dive into the election results. If cities of each county were listed, election results would be able to determine the number of voters in each city per county. 

## Source
[election_results.csv](https://github.com/riverajacqueline/Election_Analysis/files/8693815/election_results.csv)

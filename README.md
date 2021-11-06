# SuperBowl_Squares

## Overview
Using historical super bowl data, create a 10x10 grid of super bowl squares that displays the expected payout for each
square using payouts of 25% per quarter.

Eventually:
1- add all playoff games instead of just super bowls.
2- allow for user input for the payouts

## Files
squares_scraping: gets urls for each super bowl on pro-football-reference, then scrapes each page for team names
as well as scores for each quarter. returns list where first element is names (nfc, afc), and second element is
quarter score ([[nfc_1, nfc_2, nfc_3, nfc_4], [afc_1, afc_2, afc_3, afc_4]])
WORKING!!!!
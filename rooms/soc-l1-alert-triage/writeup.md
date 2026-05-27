# SOC L1 Alert Triage

**Platform:** TryHackMe  
**Difficulty:** Easy  
**Date:** 5/27/26

## What the room covers
The room covered SOC alerts at Level 1 looking at the dashboard and deciding what threats should be looked at first and what is a true positive or false.

## What I did
I had to open up the tryhackme SIEM dashboard and filter through the alerts by what was not completed yet,
then by the critical alerts and finally sorted by the age of the alert completing the oldest ones first

I opened up the alert and read through to decide whether or not it was a true positive or false positive
if it was false I marked it as false wrote a comment detailing why it was a false positive and then closed the alert.
If it was a true I marked it as a true positive and wrote a comment detailing why it was a true positive and why it was escalated then I closed the alert.

## What I learned
I learned how to filter alerts by prioritizing critical alerts and oldest alerts first I do this because detection engineers have designed rules
that give an alert a severity based on how likely it is to be a real threat and I sort by oldest because the attacker is 
more likely to be dumping the data while the newcomer has just started.

I learned what actions to take once I've picked an alert, I first assign the alert to me and put it in progress so no other people try to solve the alert.

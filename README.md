# Module_3_Challenge
This crypto arbitrage program anlyzes and presents arbitrage opportunities between coinbase and bitstamp exchanges. It compares the data between these two exchanges and analyzes arbitrage opportunies on three different dates. One date is selected from early, middle and last period. Each dae is picked based on visual inspection of the data.

Technologies

This project is written in python. The required libraries are as follows pathlib ver 2.3.6, sys version 20160418, %matplotlib inline

Usage

This project has performed data analysis.

Analysis Report

Assumptions - Based on visual data, it was assumed that bitstamp is usually priced cheaper than coinbase. However, there have been instances where coinbase has been priced cheaper than bitstamp. But for this exercise all the arbitrage opportunities are calculated as coinbase v.s. bitstamp.

Analysis - The spread was more prominent and wider in the earlier period and it reduced in the later period. The frequency of such arbitrage opportunities is more in the earlier period as compared to later period.

Comparison of Spread returns over three dates (one in each early, middle and late period). It is clear that the arbitrage opportunities have diminished over time. This is true in both the frequency and magnitude of arbitrage spread. For a given threshold of 1%, there are no arbitrage opportunites on the date in the late period. However, there 73 opportunities in early date and 3 opportunities in middle date. The max arbitrage profit on early date was 5% whereas only 1.27% on middle date and none in last date.

Early date analysis - Early date analysis was done on 16th Jan 2018. There were opportunities in the early part of the day, which then ceased to exist during the mid portion of the day and then the arbitrage opporunities picked up in the later half of the day. There seems to be some correlation between trading hours and artibitrage opportunities.

Middle date analysis - Middle date analysis was done on 24th Feb 2018. Thwere were steady opportunities through out the day and then the arbitrage opportunities picked up towards the later part of the day. Again there seems to be some correlation between late trading hours and arbitrage opporunities.

It is worth noting that the profit per trade has diminished quite significantly between early date and middle date, clearly indicating lack of arbitrage opportunities in the market as the market matures over time.

# speedtest
Broadband speed testing and analysis

So, basically my broadband is not very good and I wanted some stats
Sure, I could routinely go to fast.com or other sites and get a result but in order to 
get trends and be able to play about a bit I wanted to look into something a bit more
automated

Feel free to use copy or whatever

<b>speedtest.ipnb</b>

The original google colab notbebook I used to develop the scripts

<b>gather_speedtest.py</b>

The main script which will gather and save speedtest data on a periodic basis
idea is to cron this to run at a regular interval
Saves data to a text file - appends a line of json in a string - so not in and 
of itself a json document but each line can be read and then json.loads() will do its thing

requires speedtest_cli - from ???

<b>still to be developed</b>

aggregating the gathered stats and analysing them


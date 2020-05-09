# Intrinsic-Value-Updater
This program uses a csv containing tickers and intrinsic values to download the current price and email an account researched companies below intrinsic.
IF there are issues with email working you need to disable security settings in gmail. You can find how to online with a quick google search.
In the future I am hoping to used telegram instead of email. This code is currently run on a raspberry pi using crontab to schedule updates. If
it is run on a windows computer, scheduler will need to be used to get it to run at scheduled times.

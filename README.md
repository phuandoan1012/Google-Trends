# Google Trends
Task: Collect weekly and daily data for the keyword 'bitcoin' since 2015-01-01. Jupyter notebook and Python is used for this task. 

This repository includes:
- Code file: pythonCode.ipynb
- Exported data folder: includes 2 csv file exported from running the code
- README file to explain about my work

## 1. My idea: 
- For the daily data: The available library is used for this kind of data.
- For the weekly data:
As noticed, depending on the timeframe, Google Trends will provide the data with different frequencies. For example, for the same keyword 'bitcoin' but if we choose the timeframe from 2015-01-01 until now, the collected data will be monthly data. However, if we choose the shorter timeframe for this keyword (from 2015-01-01 to 2020-01-01, which is 5-year period) we can collect weekly data. That's why I decided to collect two dataframes for this purpose, including one from 2015-01-01 to 2020-01-01 and one from 2020-01-01 until 2022-09-18 (the day I wrote this code). After that, I merge two dataframes into one dataframe and export it to a csv file as required.

## 2. Amount of time to finish the code:
Actually, it takes only a morning to finish this code, including the time to research about Google Trends (I wasn't familiar with Google Trends before and I didn't know anything about it), the time to come up with an idea how to get daily and weekly data and the time to write and run the code successfully. 

However, it took me more than a day to finish it because at first, I tried to finish the old version of the assessment which includes hourly data, and I got the error code 429 due to Google rate limit and tried to figure out the solution. From my research, I thought there are two solutions for this problem:
- Reset the router/modem so that Google Trends recognize me as another IP address.
- Use the proxies as instructed in the pytrends documentation web page.

I tried two ways but it was still difficult for me to finish the work. After that, I messaged Terra Li to get some hints and I knew that the assessment was updated one day before and I need to do only weekly and daily data. Just let you know what I did with this problem and why it took me a lot of time to finish this assessment.

## 3. Different ways I tried:
At first, I thought the daily data can be retrieved by the same approach as I did with the weekly data (to split the timeframe into many timeframes to get many dataframes and merge it at the end to get the complete data), but I think it takes time a lot. So to save time for me and for the hiring committee, I decided to use the available library to get this kind of data. For weekly data, I didn't try any other approaches to get this data.

## 4. How to execute my program:
My code was written in Jupyter notebook. In my case, I use Anaconda to run Jupyter notebook to open the code file, and I recommend to use Jupyter notebook to read all my explanation besides my codes. The code was already run and displayed some results. If you want to run it again, please uncomment two commands to install and update pytrends library (by clicking > button which is Run button) and comment it again to run it. In addition, this code was written on 2022-09-18, so if you run it on another day, please edit the timeframe in the cell [4] in the notebook before running it. Finally, you can click >> button (Restart the kernel and run all cells again) to run all the codes again to check if necessary. 

## Improvement strategies in the future:
- If I have more time, I try to retrieve daily data by the approach that I mentioned in the #3 part to get more accurate results, I think.
- My solution may not be perfect, I really would like to hear your feedbacks and some other things I can improve in the future. Thanks for reading up to here!!






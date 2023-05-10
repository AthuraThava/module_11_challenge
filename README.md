# Module_11_challenge
### Submission Date: May 10,2023

## Step 1: Find unusual patterns in hourly Google search traffic

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/a34efc38-1d1f-4040-b272-85395c30622d)

**Do any unusual patterns exist?**

The search trends during May 2020, starts of with a high search trend value at the beginning of the day. Then graudually falls to a single digital search trends value by the time range of 8:00:00 - 10:00:00. The search trend value then increases to a higher value by the end of the day. This pattern repeats through the rest of the month for each day, creating a bouncy sideways trend pattern.

**Did the Google search traffic increase during the month that MercadoLibre released its financial results?**

The total monthly search traffic for May 2020 is: 38181
The total monthly median search traffic across all months is: 35172.5
The Google search traffic increased by 3008.5 during May 2020 when MercadoLibre released its financial results.

## Step 2: Mine the search traffic data for seasonality

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/468d9d19-25eb-49c5-9aaf-9fe4f0635e5e)

**Does any day-of-week effect that you observe concentrate in just a few hours of that day?**

The search concentration on days 5 and 6 is greater then the concentration on days 0 to 4 during the 6th hour. This change in concentration shifts the heatmap concentration for days 5 and 6 for the remainder of the day. The search concentration is more saturated before the 3 hour window and after the 20 hour window.

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/6c3b4747-850c-4436-bfab-af0116e39fb4)

**Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?**

The search trend during the winter holiday period (Weeks 40-52) increases until the week 51, excluding the small drop from weeks 40-42. The trend drastically drops down to a search trend value of 47 for week 52, one of the lowest points throughout the year.

## Step 3: Relate the search traffic to stock price patterns

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/4f5c6f1d-cca1-438d-aca4-6637a9a54ca6)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/0751d14c-9739-4f06-91dd-aedb68625c9d)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/018ba302-2bcd-498f-8901-16f13fb3c15c)

**Do both time series indicate a common trend that’s consistent with this narrative?**

Both time series indicate a common trend throughout the period of January - June 2020. During the pandemic both time series trends had a downward drop from 02/25/2020 to 03/11/2020 creating a bear market for MercadoLibre. The introduction of new customers and revence in the e-commerce industry allowed the serach trends to recover. The stock market continued on a downward trend till 04/03/2020. When the increase in e-commerce revenue started affecting the market, MercadoLibre's closing prices started increasing as the search trend had.

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/6877ca47-6857-4a33-8787-652d0a43e3d7)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/cba3474f-5b8c-491c-ba24-c00c97b923f6)

**Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?**

Stock volatility and lagged search traffic are correlated negatively, while hourly stock returns and lagged search traffic are correlated positively.

## Step 4: Create a Time Series Model with Prophet

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/aae12e9a-009e-4fbb-83ba-5a982cc2918b)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/867d58e0-d6b4-406e-bd1b-f96b91d151a2)

**How's the near-term forecast for the popularity of MercadoLibre?**

The near-term forecast for the popularity of MercadoLibre predicts a negative downward trend.

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/4819ffba-df80-4b58-a918-b1431d810c46)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/36af8c9b-68f3-4176-834f-9b4236578771)

**What time of day exhibits the greatest popularity?**

The time of day that exhibits the greatest popularity is at 0:00:00 at the beginning and ending of the day.

**Which day of week gets the most search traffic?**

Tuesday is the day with the most search traffic.

**What's the lowest point for search traffic in the calendar year?**

The lowest point for the serach traffic in the calendar year is mid-october.

## Step 5 (Optional): Forecast Revenue by Using Time Series Models

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/46fc0d7b-35d3-4e0d-9896-489b18ccdfa4)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/f5f40714-e347-45a7-b3a7-811f33437157)

**For example, what are the peak revenue days? (Mondays? Fridays? Something else?)**

The peak revenue days in the week is Wednesday, followed by Monday.

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/b94ad96e-33b7-4144-86c5-5ab55e1e363b)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/74014a63-fbdd-4520-8d3a-a8947d4fcb56)

![image](https://github.com/AthuraThava/module_11_challenge/assets/125240804/b4c5f631-c373-4cfc-a0b5-3bbad55d4555)

**Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.**

According to the forecast, the most likely situation is 970, while the best case is 1052 and the worst case is 886.

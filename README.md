# Internet-Analysis
# User story and task

My friend while using mobile data noticed he was facing major network fluctuations and hence wants to identify the best and worst time during a day for best internet usage based on various factors as mentioned in the next section. Analyse the log file given to better understand the situation and apply data science skills to clean, model and analyse the data to provide him answers to the questions asked in later sections of this document. Make use of the analytics sheet for better visualisations and plot graphs.

# Best conditions

- Latency: lower the better
- Jitter: lower the better
- Download: higher the better
- Upload: higher the better
- Packet Loss: 0.0%

# Analysis of days

1. Which day was the **best** in terms of **average latency**? Thursday
2. Which day was the **worst** in terms of **average latency**? Tuesday
3. Which day was the **best** in terms of **average jitter**? Tuesday
4. Which day was the **worst** in terms of **average jitter**? Sunday
5. Which day was the **best** in terms of **average download speed**? Sunday
6. Which day was the **worst** in terms of **average download speed**? Saturday
7. Which day was the **best** in terms of **average upload speed**? Friday
8. Which day was the **worst** in terms of **average upload speed**? Wednesday
9. Which day was the **best** in terms of **average packet loss**? Thursday
10. Which day was the **worst** in terms of **average packet loss**? Monday
11. Which day had the **most network outages**? Tuesday
12. Which day had the **least network outages**? Thursday

# Analysis of hours

1. Which hour was the **best** in terms of **average latency**? 01
2. Which hour was the **worst** in terms of **average latency**? 09
3. Which hour was the **best** in terms of **average jitter**? 14
4. Which hour was the **worst** in terms of **average jitter**? 23
5. Which hour was the **best** in terms of **average download speed**? 04
6. Which hour was the **worst** in terms of **average download speed**? 22
7. Which hour was the **best** in terms of **average upload speed**? 02
8. Which hour was the **worst** in terms of **average upload speed**? 20
9. Which hour was the **best** in terms of **average packet loss**? 07
10. Which hour was the **worst** in terms of **average packet loss**? 06
11. Which hour had the **most network outages**? 08
12. Which hour had the **least network outages**? 00, 01, 02, 11, 16, 18, 20, 23

# Overall analysis

1. When would be the **best** time for **downloads** for each day?

Ans: Mon - 04.00

Tue - 02.00

Wed - 03.00

Thu - 03.00

Fri - 04.00

Sat - 03.00

Sun - 04.00

2. When would be the **best** time for **uploads** for each day?

Ans: Mon - 02.00

Tue - 02.00

Wed - 03.00

Thu - 03.00

Fri - 04.00

Sat - 03.00

Sun - 05.00

3. Which would be the **best day and hour for low latency** activities?

Ans: Thu 02

4. Which was the **most connected server**?

Ans: Airtel Broadband - Chennai

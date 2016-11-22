---
title: Seasonal ARIMA Lab
type: lab
duration: "1:25"
creator:
    name: Robby Grodin
    city: BOS
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Seasonal ARIMA Lab

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

Now that we've trained a fairly straightforward Season ARIMA model, we're going to look at a slightly more complex case. You've been contracted by a large pharmaceutical company to help improve their sales predictions. Some medicines follow very predictable patterns, but are largely affected by external factors. For example, while cold medicine has strong seasonal patterns, shifts in global temperature and differences in birth rates can have non-seasonal affects on sales data.

We're going to investigate sales of a Corticosteroid drug in Australia. They are a class of steroid hormones used to treat anything from brain tumors to skin diseases. Our data set contains 203 observations of drug sales over the course of 1991-2008 sampled monthly. Each observation is reported as Millions of scripts per month.

Their head Data Scientist will be meeting with you to discuss your findings. They will expect you to report top level findings in the form of a text document (this won't be client facing, just log your observations in a neat format), supported by a code walk-through where you should be prepared to defend your decisions.

**NOTE:** Being able to explain a choice is more important than whether or not you make the right decision, not only in interviews but in every interaction you will have as a Data Scientist.

## Exercise

#### Requirements

- Load in the data and perform EDA. Record your observations regarding trend, seasonality, stationarity, etc.
- Clean the data if needed and perform any transformations you deem necessary. Don't forget to document the decisions you made, and why you made them!
- Be sure to plot ACF/PACF along the way, and record any observations you may have.
- Keep a log of each model you audition, along with their AIC values (Dickey-Fuller Test). You should be auditioning at least half a dozen models.
- Determine if Seasonal Differencing is needed. Make a note as to your decision, with graphical evidence to support.
- Clearly address the logic behind your choices for all 7 terms (3 seasonal, 3 non-seasonal, and seasonal periods).
- Utilize the Ljung-Box test to determine fit for your model (Dickey-Fuller Test). Record all observations.
- Provide both in-sample ("using current data to correlations") and out-of-sample ("using past data to make forecasts of the future") forecasts for at least 3 different models. Summarize the resulting RSME values in your iPython notebook.

#### Starter code

Training wheels are off! You'll be starting this one from scratch. By now you should be comfortable loading data into an ipython notebook, so we'll let you take it from here.

#### Deliverable

You are expected to audition at least 6 different ARIMA models, and provide forecasts for 3 of them. A clear and easy to read log of your observations will be needed to back up the decisions made in your code.

Your code should be properly documented in an iPython notebook.

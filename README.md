Event Study on EV & Supplier Stocks

This project conducts an event study analysis on Electric Vehicle (EV) companies (Tesla, BYD, NIO, Rivian, Lucid) and their supplier networks (CATL, Panasonic, LG Energy Solution, Samsung SDI, Rio Tinto, Gotion).

The objective is to measure the impact of policy, subsidy, and tariff announcements on stock returns and to quantify spillover effects from EV firms to their suppliers.

🔍 Features

Stock price data sourced from the Bloomberg Terminal.

Merge financial data with event-tagged news (policy, subsidy, tariff, news).

Compute:

Abnormal Returns (AR)

Cumulative Abnormal Returns (CAR)

Average Abnormal Returns (AAR)

Cumulative AAR (CAAR)

Event window analyses (e.g., [-5,+5], [-1,+1]).

Statistical inference:

T-tests, Welch tests, Mann–Whitney tests.

OLS regressions with clustered standard errors.

Visualization:

AR/CAAR time series.

CAR distributions by firm.

Spillover regression plots.

📂 Project Structure

EV stock data: Tesla, BYD, NIO, Rivian, Lucid (Bloomberg).

Supplier stock data: CATL, LG Energy Solution, Panasonic, Samsung SDI, Rio Tinto, Gotion (Bloomberg).

Event dataset: Policy-related news tagged as subsidy/tariff/policy events.

Key Outputs

Firm-wise CAR distributions.

CAAR time trends across events.

Positive share of CAR events (%).

Supplier spillover coefficients with 95% CI.

📊 Event Study on EV & Supplier Stocks

  This project performs an event study analysis on major Electric Vehicle (EV) companies — Tesla, BYD, NIO, Rivian, Lucid — and their supplier networks — CATL, Panasonic, LG Energy Solution, Samsung SDI, Rio Tinto, Gotion.
  
  The goal is to measure the impact of policy, subsidy, and tariff announcements on EV stock returns, while also quantifying spillover effects on suppliers.

🔍 Features:

  Stock price data sourced from the Bloomberg Terminal
  
  Integration of stock data with event-tagged news (policy / subsidy / tariff)

📊 Computations:

  Abnormal Returns (AR)
  
  Cumulative Abnormal Returns (CAR)
  
  Average Abnormal Returns (AAR)
  
  Cumulative AAR (CAAR)
  
  Event window analysis: [-5,+5], [-1,+1]

🧮 Statistical inference:

  T-tests, Welch tests, Mann–Whitney tests
  
  OLS regressions with clustered SEs

🎨 Visualization:

  AR/CAAR time series
  
  Firm-level CAR distributions
  
  Spillover regression plots

📂 Project Structure:

  EV stock data → Tesla, BYD, NIO, Rivian, Lucid (Bloomberg)
  
  Supplier stock data → CATL, LG Energy Solution, Panasonic, Samsung SDI, Rio Tinto, Gotion (Bloomberg)
  
  Event dataset → Policy-related news tagged as subsidy/tariff/policy

📊 Key Outputs:

   Firm-wise CAR distributions
   
   CAAR trends across event windows
   
   % of events with positive CARs
   
   Supplier spillover coefficients with 95% CI

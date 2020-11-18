![image1](https://www.anthesisgroup.com/wp-content/uploads/2020/06/noun_investation_2724933-1.png)

# ESG vs. SIN

---

## Team Members:

P. Alex Hertel, Akrem Mohammed, Jeff Myers, Lam Nguyen

---

### Introduction:

Our objective was to compare and contrast a portfolio comprised of ESG companies vs. a portfolio comprised of SIN companies. We were aiming to draw conclusions using price performance, key event scenario analysis, risk management techniques, and Montecarlo simulations. We were expecting to test various scenarios and hypothesis using the above techniques to choose a portfolio that is most suitable based on the portfolio management framework.

### Defining ESG & SIN:

Before collecting and scrapping the data, we defined ESG and SIN. Environmental, social and governance (ESG) criteria are a set of standards for a company's operations that socially conscious investors use to screen potential investments. For our purposes SIN is defined as the opposite of ESG. 

### Data Collection/Scrapping:

After defining our objective and defining the difference between ESG and SIN, we started with a top-down approach to scrapping and collecting the data. We used the S&P 500 stocks as our starting point and using Yahoo Finance’s ESG ratings and the use of the Beautiful Soup Library we were able to stack rank all 500 companies by ESG rankings. Filtering and scrapping further we narrowed our ESG portfolio to 33 companies and our SIN portfolio to 39 companies, respectively. The difference is due to null values and outliers. 

### Analysis/Plotting:

Slicing the data by time frame we analyzed our portfolios during the financial crisis, flash crash, Brexit, longest government shutdown, yield curve inversion, and most recently the Covid Crash. We then simulated 15 years of future market returns using a Montecarlo simulation. 

### Conclusion:

The ESG portfolio yielded higher returns compared to the SIN portfolio in every scenario including the Montecarlo simulation. 

### Feedback/Errors:

In conclusion our data had some flaws. Utilizing Yahoo Finance and their third party ESG rating system the ESG portfolio was heavily skewed towards the technology sector.  The SIN portfolio was heavily weighted towards energy and industrials. Comparing the tech sector against energy and industrials over that 12-year time frame, one would find tech yielding higher returns.  Another potential flaw was not defining a benchmark, to accurately compare the performance of portfolios there should be a defined benchmark i.e. the S&P 500. Due to time constraints we failed to plot a benchmark. Finally, as with all portfolio management and analyzing past trends, past performance doesn’t guarantee future results. 

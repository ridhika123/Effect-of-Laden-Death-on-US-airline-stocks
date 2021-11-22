# Osama Bin Laden's Death: Effect on US airline stock prices

## Abstract
The 9/11 attacks shocked the world and the stock market negatively. We hypothesize that the announcement of the death of Osama Bin Laden on May 2nd, 2011 would shock the stock markets positively. In order to investigate the effect of the death of Bin Laden on stock prices of US airlines we conduct an event study analysis using the Fama French Three Factor model. We use daily stock price data of nine publicly traded US airlines and find that our hypothesis is confirmed. Further, different airlines are differentially impacted by the shock. We conclude that there is a correlation between market size of an airline and the magnitude of the impact by the shock.

## Data
* Daily stock price data from Yahoo Finance on nine public US airlines, namely, Alaska, Allegiant, American, Delta, Hawaiian, Skywest, Southwest, Jetblue and United airlines.
* Fama French Three Factor Model data is [here](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/ff3fm_data.dta).

## Code
#### Osama Bin Laden's Death
* Data used: [ALK](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/ALK.dta), [ALGT](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/ALGT.dta), [AAL](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/AAL.dta), [DAL](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/DAL.dta), [HA](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/HA.dta), [JBLU](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/JBLU.dta), [SKYW](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/SKYW.dta), [LUV](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/LUV.dta), [UAL](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/UAL.dta), .

[alaska_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/alaska_2.dta), [allegiant_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/allegiant_2.dta), [american_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/american_2.dta), [delta_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/delta_2.dta), [hawaiian_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/hawaiian_2.dta), [jetblu_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/jetblu_2.dta), [skywest_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/skywest_2.dta), [southwest_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/southwest_2.dta), and [united_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/united_2.dta).

* [prepping_yahoo_data](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/prepping_yahoo_data.do): Prepping combined airlines data using FF3FM model. 
* [single_event_construct_ff3fm_coefficients](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_construct_ff3fm_coefficients.do): Constructing the coefficients.
* [single_event_graphical_analysis](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_graphical_analysis.do): Graphical analysis of effect of Osama Bin Laden's death on stock prices of nine US airlines.
* [single_event_regression_analysis](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_regression_analysis.do): Regression analysis of effect of Osama Bin Laden's death on stock prices of nine US airlines.

#### 9/11 
* Data used: [911_LUV](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_LUV.dta), [911_SKYW](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_SKYW.dta), [911_ALK](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_ALK.dta), [911_southwest_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_southwest_2.dta), [911_skywest_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_skywest_2.dta), and [911_alaska_2](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/911_alaska_2.dta).
* [prepping_yahoo_data 911](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/prepping_yahoo_data%20911.do): Prepping combined airlines data using FF3FM model.
* [single_event_construct_ff3fm_coefficients 911](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_construct_ff3fm_coefficients%20911.do): Constructing the coefficients.
* [single_event_graphical_analysis 911](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_graphical_analysis%20911.do): Graphical analysis of effect of 9/11 on stock prices of three US airlines.
* [single_event_regression_analysis 911](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/single_event_regression_analysis%20911.do): Regression analysis of effect of 9/11 on stock prices of three US airlines.

## Final Output
Final paper can be found [here](https://github.com/ridhika123/Effect-of-Laden-Death-on-US-airline-stocks/blob/main/Bin%20Laden%E2%80%99s%20Death%20-%20Effect%20on%20US%20airline%20stock%20prices.pdf).

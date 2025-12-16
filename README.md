# Determinants of High Hotel Ratings: Using data about Berlin hotels
The analysis sample consists of **559 hotels located in Berlin**, drawn from the *hotels-europe* dataset after applying cleaning and selection criteria. The dataset combines hotel features with pricing information, allowing for an examination of factors associated with high customer ratings in a major European city.

The dependent variable in the analysis is a binary indicator, `highly_rated`, which equals 1 if a hotel’s average user rating is **at least 4 out of 5**, and 0 otherwise. In the final sample, approximately **56.4% of hotels are classified as highly rated**, indicating a relatively high overall level of customer satisfaction among Berlin hotels.

Key explanatory variables include **distance to the city center (in kilometers)** and **hotel star classification**, which serve as proxies for location attractiveness and service quality, respectively. The average hotel in the sample is located **2.80 km from the city center** and has **3.29 stars**, suggesting that most hotels are mid-range and centrally accessible.

Hotel prices vary substantially across the sample. The median-based hotel-level price measure has a mean of **€128.28 per night**, with a right-skewed distribution and a small number of high-price observations exceeding **€1,500**. To avoid overweighting hotels with many price observations, prices were aggregated to the hotel level using the **median price** across booking conditions. No further transformation of prices is used in the main analysis, as price serves only as a descriptive characteristic rather than a dependent variable.

Overall, the sample is sufficiently large and heterogeneous to support econometric analysis using both linear and nonlinear probability models. The binary nature of the outcome variable motivates the use of **Linear Probability, Logit, and Probit models**, allowing for a comparison of results across alternative estimation approaches.

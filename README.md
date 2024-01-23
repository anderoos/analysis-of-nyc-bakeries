# Analysis of NYC's Dessert Sector
Status: __Work in Progress__
## Featured Files
* [Data Request](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/bakery_csv_retreival.ipynb)
* [Data Cleaning](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/bakery_data_cleaning_v2.ipynb)
* [Main Analysis](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/summary_analysis.ipynb)
* [Presentation](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/presentation_draft.pptx)
## Abstract
New York City is often crowned as one of the most diverse places on earth. With about 200,000 small businesses operating in New YorK City, its one of the most competitive places in the US to operate a business. In this compettive space, people often ask 'is it even worth opening a business in NY?'. In this exploratory analysis, I attempt to uncover what are the best business opportunities are in NYC for bakeries and desserts using yelp's API.
## Figures
![category-proportion](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/category-dist.png)
![distribution-of-reviews](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/rating_vs_label.png)
![mean-differences](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/meandiffs.png)
![means-review-count](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/label_mean.png)
![median-review-count](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/label_med.png)
![phone-number-effect](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/phone_num.png)
![manhattan-dbscan](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/manhattan_cluster.png)
![bk-dbscan](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/brooklyn_cluster.png)
![qns-dbscan](https://github.com/anderoos/dv-analysis-of-nyc-bakeries/blob/main/Images/queens_cluster.png)
## Conclusions
   * Dessert-focused businesses in NYC face many challenges but given the right business model and location, can see success.
   * Bakeries comprise about 26% of dessert cohorts.
   * Cupcakes, cakeshops, ie ‘single specialty’ shops are not as popular and do not see high foot traffic.
   * Coffee and drinks may be an entry point for many new customers since we see the higher review_counts in these categories.
   * Given the popularity of non-dessert categories, savory menu items may entice customers.
   * Based on the clustering model used, certain locations see much higher foot traffic compared to others.

## Limitations
   * Does not account for population density of local neighborhoods.
   * Does not account for the age of the business.
   * Does not account for social media presence. With emergence of reels and tiktok, some social media presence can have a significant impact on foot traffic.
   * Foodie culture: We cannot account for social media influences on a business’ reviews and review_counts

## Task List
* Bin review_counts and re-perform cluster analysis
* Take a second look at DBSCAN centroids
* Create interactive dashboard for DBSCAN clusters
* Deploy using Gitpages

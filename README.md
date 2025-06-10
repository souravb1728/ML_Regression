# DS_Online_Marketing_Performance

**Here we are going to analyze a dataset related to online marketing performance**
- **First we will perform a Descriptive Analysis using Visulaization and try to infer important observations**
- **Then we will perform Linear and Non-Linear Regression on the dataset to create a Model and check its accuracy**

Information on the data >
Data provides information on online ad campaigns and related conversions in terms of Post Click Conversions and Post Click Sales Amount. 
It also provides cost of each campaignon the Revenue column. 
We will change the column names to more meaningful names to avoid confusion. 
We will convert the month and day to date for easier analysis. 
We can find the Net sales from a campaign after deducting the cost of the campaign. 


## Descriptive Analysis
Here we have considered 4 target variables > Clicks(Number of Clicks), Revenue(Cost of Campaign), Post Click Conversions and Net Sales. We will analyze all these target variables w.r.t the features one by one and draw inferences accordingly.

### Analysis of target variabes w.r.t campaign_number(campaignType)

Basic Analysis Result >
1. Type1 > 56% NoOfClicks with conversion rate 97% and sales amount 95% (overall cost 83%)
2. Type2 > 35% NoOfClicks with conversion rate 2% and sales amount 3.5% (overall cost 13%)
3. Type3 > 8% NoOfClicks with conversion rate 0.7% and sales amount 1.5% (overall cost 4%)

Inferences drawn >
1. Type1 is definitely the best among the campaign types with a overall conversion rate of 97% and overall Sales of 95%. But we can see the NoOfClicks% is low comapred to the sales% it generated. The company x should focus on Type1 to get more no of overall clicks so it geneartes even more sales.
2. Type2 is the least performer of all. Even though it genaerates significant overall click% but that does not convert into Sales as much. Company X needs to rethink its conversion strategy for Type2 or design a new strategy to target Type2 requirements.
3. Type3 performs better compared to Type2. With the least clicks and conversion, it generates 1.5% with an cost of 4%. company X should focus on stategy to gain more clicks on Type3, they need to rethink on how to attract customers in this segment at least to click the ad.

### Analysis of target variabes w.r.t user_engagement

Inferences drawn >
1. Medium engagement involves significant NoOfClicks% (43%) and significant cost% (21%) but generates only 6% of overall sales. Company X needs to work on strategies to improve the conversion rate on campaigns where user engagement is medium

   
### Analysis of target variabes w.r.t placement(Channel)

Basic Analysis Result >
1. channel 'ghi' involves 50% click%, conversion rate 52% generating 50% overall sales%
2. channel 'mno' involves 40% click%, conversion rate 40% generating 41.5% overall sales%

Inferences drawn >
1. Thses 2 channels ('ghi' & 'mno') draws 90% traffic and contribute to 91.5% overall sales%. company X needs to make strategies to keep the momentum going for these 2 channels and make sure the interaction through these channels remains smooth and flawless for the users/customers.
2. channel 'abc' do not have any prospect.
3. Channel ('def' & 'jkl') has some potential. Particularly if we look at channel 'jkl' with only 3% click%, only 3% conversion, overall cost 3% but generates 3.3% of sales%. If the NoOfClicks and the Conversion rate is improved for this channel, it could generate sales at a higher rate.

### Analysis of target variabes w.r.t banner

Inferences drawn >
1. Thses 3 banners draws 85% traffic and contribute to 86% overall sales%.
2. (800 x 250), (468 x 60), (670 x 90) these banners have almost no contribution to the sales. So these banners can be dropped from campaign.
3. Among the top performers banner (300 x 250) could be utilized more compared to others as it generates sales at a higher rate 19% compared to its cost 15.5%

### Analysis of target variabes w.r.t display(number of ads)

Inferences drawn >
1. Type1 has a quite linear relationship
2. Type3 is very less responsive to the change in display.
3. Type2 shows good response on a display range < 40000. company X needs to think how to improve beyond this range


### Analysis of target variabes w.r.t campaign type and channel

Inferences drawn >
1. camp1 + 'mno' > has much potential as it generates 39% sales from 28% overall cost
2. camp2 can drop some channels > 'abc' and 'jkl'. Channel 'ghi', 'mno' has good potential with overall click 31% but sales only 1.5% with cost 5.5%. company X should come up with strategies to increase the conversion rate to generate more sales with thses channels

### Analysis of target variabes w.r.t Date

Inferences drawn >
1. We observe, NoOfClicks decreases rapidly after the first month of campaign but sales do not decrease at the same rate and continue to generate significant amount. Company x should devise strategies on how to increase no of clicks on the last 2 months so it can help generate more sales on last 2 months


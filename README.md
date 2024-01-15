# MindTheGap_wxbiz_game_course

Weather-sensitive business game-course materials. 

Instructor_PrepareHindcastDataset has tools for setting up a corpus of real weather-model "forecast data" from the spoofed year "1234" (honor system not to peek/cheat at the real-world year these came from). 

These data (verification, and forecasts at each lead time) are unveiled, day for day, as the game proceeds. 

Each class session, codes in Jupyter notebooks score the verification payout, and strategize the preparations for the next session and the rest of the semester. 

1. Weather verification grids are geographically sampled at a portfolio of 'business sites', and spatially downscaled (random noise is added to model grid point data). 

These data are converted to damages and payouts according to a weather-conditional payout table contrived for the business/sector being gamed out. Damages and profits are discounted/adjusted based on Preparations_CostsBenefits.csv, which were set previously in a prior "turn" of the game.  

2. Players then update their Preparations, based on the "newest" forecasts unveiled for this session. Each kind of preparation has its contributions to Preparations_CostsBenefits.csv. 

Preparation decisions range from short to long horizons: 

a. Short term adjustments (e.g. in personnel and asset redeployment),

b. Medium term costs (e.g. supply-chain orders, insurance adjustments) 

c. Long term investments (e.g. in applied research about strategies) 



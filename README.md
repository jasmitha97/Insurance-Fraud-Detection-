# Insurance-Fraud-Detection

All first-party physical damage claims will be filtered by claim handlers and some of them will be referred to the fraud detection team. Your data is a sample of these referred claims from 2015 to 2016.

As a simplification, you are just going to work with the train dataset (linked below). This is because it has the answers! All teams will use the same random_seed to split the data into train and test - Dave will do this part for you. You may not delete rows in the test partition, use transform() to update rows in test partition, you can do almost anything you want on the train partition. If there is data leakage, you automatically go into last place (more on that later.)

Your work is to build a model on the training data and apply your model to predict the fraud indicator for each claim in the test data.

Variable Descriptions

claim_number - Claim ID (cannot be used in model)
age_of_driver - Age of driver
gender - Gender of driver
marital_status - Marital status of driver
safty_rating - Safety rating index of driver
annual_income - Annual income of driver
high_education_ind - Driver’s high education index
address_change_ind - Whether or not the driver changed living address in past 1 year
living_status - Driver’s living status, own or rent
zip_code - Driver’s living address zipcode
claim_date - Date of first notice of claim
claim_day_of_week - Day of week of first notice of claim
accident_site - Accident location, highway, parking lot or local
past_num_of_claims - Number of claims the driver reported in past 5 years
witness_present_ind - Witness indicator of the claim
liab_prct - Liability percentage of the claim
channel - The channel of purchasing policy
policy_report_filed_ind - Policy report filed indicator
claim_est_payout - Estimated claim payout
age_of_vehicle - Age of first party vehicle
vehicle_category - Category of first party vehicle
vehicle_price - Price of first party vehicle
vehicle_color - Color of first party vehicle
vehicle_weight - Weight of first party vehicle
fraud - Fraud indicator (0=no, 1=yes). This is the response variable.

# WTA_Earnings
A project to analyze lifetime earnings of women tennis players.  Relies on data from http://wtatennis.com
The current data is located at https://wtafiles.wtatennis.com/pdf/rankings/All_Career_Prize_Money.pdf

## TODO:
1. ~~Split the player name into first name and country~~
  * ~~Create DataFrame with the new elements~~
  * ~~Create an HTML table~~
2. Create basic EDA charts
  * ~~log-log of earnings vs Rank~~
  * ~~histogram by country~~
  * ~~how many girls without a country have a name ending in OVA?~~
  * ~~what are the last three letters of all girls without a country?~~
3. ~~Create a link to Wikipedia listing~~
4. Validate Wiki link and provide stats
  * will be generated as byproduct of item **5**
5. Scrape Wiki for extra player info:
  * Country
  * Birthday/Age
  * Height
  * Year Turned Pro
  * Year Retired
  * Prize Money (to validate against WTA)
  * Career Win/Loss Record
  * Titles
  * Highest Rank
  * Singles vs Doubles Earnings
6. Data cleaning
7. Advanced EDA
  * Are tennis players getting taller: height vs age
  * Does height correlate with rankings?  Are taller players better?
  * Does height correlate with earnings?
  * Is height dependent on the country?
  * Is height increasing over time?
8. Build Predictive Model For Earnings

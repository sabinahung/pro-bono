# pro-bono
This is a project exploring definitive factors that affects pro bono performance at big lawe firm. I did a multivariable regression analysis with Am Law data and found that profit margin stands out to be a statistically significant factor for both 

### Data collection
The data is collected from the 2024 national report of [American Lawyer Pro Bono Scoreboard](https://www.law.com/americanlawyer/2024/07/09/the-2024-pro-bono-scorecard-national-report/). I then combined the pro bono data with the minority representation data and women in law data in [2024 Diversity Scorecard](https://www.law.com/americanlawyer/diversity-scorecard/) and financial data from [Am Law 100](https://www.law.com/americanlawyer/am-law-100/) and [Am Law 200](https://www.law.com/americanlawyer/2024/05/07/the-2024-am-law-200-at-a-glance/).

Collection of the 2024 data was really simple (thankfully). They added a html table below their Tableau table so you could easily copy and paste them into your spreadsheet. The only hassle is probably matching the firm names because they're not documented the exact same way. For instance, 'O'Melveny & Myers' could be 'O'Melveny & Myers' or 'O'Melveny.' So most of my time was spent on fixing the `VLOOKUP()` errors and ensuring they capture the right firms. 

### Data analysis
For


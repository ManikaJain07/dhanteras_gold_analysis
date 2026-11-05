# dhanteras_gold_analysis
Gold Prices Around Dhanteras (2016 to 2025)

## Questions
1. How does the gold price behave in the 7 trading days before and after Dhanteras?
2. When was gold stable, and when was it unstable?

## Data
- Daily gold prices (USD per ounce) from Yahoo Finance (ticker GC=F), Jan 2016 to 4 Nov 2026.
- Dhanteras dates for 2016 to 2026, written by me in `dhanteras_dates.xlsx`.
- These are international prices, so they will not match the rate a jeweller shows in India.

## What I found
- After Dhanteras, gold fell in 8 of 10 years, but the falls were mostly small compared with normal weekly moves (about 2.7%).
- Before Dhanteras there was no clear pattern, except for an unusual 2025.
- Gold was calmest in 2017 to 2019 and most unstable in 2026.
- I only have 10 years of data, so this is a mild tendency, not a rule.

## My Findings in detail
### 1. The long term trend
- From 2016 to 2019 gold was calm, between about 1,100 and 1,400.
- From 2019 to 2023 it moved up to about 2,000 and then stayed around there.
- From 2024 to early 2026 it climbed very fast to about 5,300.
- Since early 2026 it has fallen back to about 4,000.
- Gold has been much less stable since 2024 than before.

### 2. What happens after Dhanteras
- I looked at the price change in the 7 trading days after Dhanteras, for 2016 to 2025.
- The price went down in 8 years and up in only 2 (2021 and 2023).
- The changes ranged from about -8.2% to +4.2%.

### 3. My first guess was half right
- I guessed that gold fell after Dhanteras up to 2021 and rose after it from 2021 onwards.
- The first half was right: gold fell in the week after Dhanteras in every year from 2016 to 2020.
- The second half was wrong: it rose in 2021 and 2023, but fell in 2022, 2024 and 2025.

### 4. The 2025 surprise
- In 2025 gold rose about 9.7% in the 7 trading days before Dhanteras and fell about 8.2% in the 7 trading days after.
- No other year came close to that.
- With all years, the average is +0.92% before and -1.25% after. Without 2025 it is -0.07% before and -0.48% after.
- So 2025 explains most of the "up before" pattern, but the "down after" pattern stays even without it.

### 5. Is Dhanteras week special?
- In any normal 7 trading day period, gold moves about 0.37% on average, and the usual size of a move is about 2.7% up or down.
- Gold falls in about 43% of ordinary weeks. After Dhanteras it fell in 8 of 10.
- In 4 of 10 years (2020, 2021, 2023, 2025) the move after Dhanteras was bigger than the usual size. In ordinary weeks this happens about 1 time in 4.
- The "before" weeks looked normal, except for 2025.

### Conclusion
- I found no clear pattern before Dhanteras.
- After Dhanteras gold fell in 8 of 10 years, which is more often than in ordinary weeks. But the falls were mostly small (about -0.5% on average without 2025), compared with a usual weekly move of 2.7%.
- I only have 10 years of data and I checked several patterns, so this could be luck. I would call it a mild tendency, not a rule.

### 6. When was gold stable and when was it not?
- I measured how much gold's price moves on a typical day, year by year.
- The calmest years were 2017, 2018 and 2019, when gold moved about 0.65% to 0.75% a day.
- 2020 was jumpy (about 1.4% a day), and 2025 and 2026 were jumpy too.
- 2026 was the most unstable year, at about 1.8% a day, nearly three times as much as 2018. The 2026 figure covers only part of the year, up to 4 November.

### 7. Falls after peaks
- After each high, gold pulled back at some point. The falls from the highest price were about 17% (end of 2016), 19% (early 2021), 21% (late 2022), 12% (early 2023) and 9% (late 2025).
- The biggest fall came in 2026. Gold dropped about 27% from its early-2026 high of about 5,300 to a low of about 3,900 on 30 October.
- It has since recovered part of that fall.
- So gold usually pulls back after big rises, but only the 2026 fall was this large.

## Files
- `dhanteras_gold_analysis.ipynb`: the full analysis
- `gold_usd.csv`: the gold price data
- `dhanteras_dates.xlsx`: the Dhanteras dates

# Memo: Should Banco Atlântico lend to customers with credit scores below 600?

**To:** Head of Credit Risk · **From:** BI Analyst · **Data:** 60 loans (after removing 1 duplicate and fixing 1 text score)

**1. Headline.** Default risk rises sharply as credit scores fall: Poor (< 580) 42.9% · Fair (580–669) 14.3% · Good (670–739) 3.3% · Excellent (740+) 0%. Poor-score loans default about 13× more often than Good-score loans; the overall book defaults at 10.0%.

**2. Why it might mislead.** The bands are small: Poor has only 7 loans (3 defaults), so one default more or less moves its rate by ±14 pp. The direction is reliable because it holds across all four bands; the exact rates are not. Default rates also ignore what each loan earns.

**3. Recommendation.** Don't open lending below 580 at current pricing. Assuming 60% of a defaulted balance is lost, a Poor-band loan loses about €26 per €100 lent a year, which no normal interest rate covers. The 580–669 band could be served, but only with risk-based pricing about 9 points above Good-band rates.

**4. Next step.** Before changing the cut-off: add each loan's interest rate and recoveries after default (real loss given default), use 2–3 years of history to get more loans per band, and recompute profit per band = interest income − expected loss − funding and operating costs.

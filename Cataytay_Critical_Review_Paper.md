**A Critical Review of “An Empirical Analysis of International Labour
Migration in the Philippines”**

*Agbola, F. W., & Acupan, A. B. (2010). Economic Systems, 34, 386–396.*

Prepared by: Cataytay

# Introduction

Many Filipinos leave the country to live or work abroad. In 2007, about
8.2 million Filipinos were living or working in more than 193 countries.
In the same year, they sent home US\$14.4 billion in remittances (money
sent home by workers abroad). Because emigration is this large, it is
important to know what causes it.

Agbola and Acupan (2010) study this question using yearly national data
from 1975 to 2005. This review explains the study’s research problem,
theoretical framework, data, methodology, key findings, and areas for
further research. It also gives a critical assessment of the study’s
strengths and weaknesses.

## Key terms

The review uses the following terms. Each term keeps the same meaning
throughout.

| **Term**                     | **Meaning in this review**                                                                                            |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Emigration                   | People leaving the Philippines to live or work in another country.                                                    |
| Migration share              | The number of Filipino migrants as a share of the Philippine population. This is what the study tries to explain.     |
| Explanatory variable         | A factor that may make the migration share go up or down, such as unemployment.                                       |
| Push factor                  | A condition at home that pushes people to leave (for example, no jobs).                                               |
| Pull factor                  | A condition abroad that pulls people in (for example, higher wages).                                                  |
| Proxy                        | A stand-in measure for something that cannot be measured directly.                                                    |
| Time series                  | Data on the same thing collected over many years, one value per year.                                                 |
| Stationary                   | A time series that moves around a stable average instead of drifting over time.                                       |
| Unit root test               | A test that checks whether a time series is stationary.                                                               |
| First difference             | The change in a variable from one year to the next.                                                                   |
| Cointegration                | When time series that drift over time still move together in the long run.                                            |
| Error correction model (ECM) | A model that shows short-run changes and how the data return to their long-run relationship.                          |
| Error correction term (ECT)  | The part of the ECM that shows how fast the data return to the long-run relationship.                                 |
| Coefficient                  | A number that shows how much the migration share changes when an explanatory variable changes.                        |
| Statistically significant    | A result that is unlikely to be due to chance. This study uses the 5% level.                                          |
| t-statistic                  | A number used to judge statistical significance. In this study, values beyond about ±2 are statistically significant. |

*Table 1. Key terms used in this review.*

# 1. Research Problem and Gap

The Philippines began sending workers abroad in the early 1970s. At
first, this was a short-term fix for high unemployment and a
balance-of-payments crisis (when a country spends more foreign money
than it earns). Over time, emigration became a permanent part of the
economy.

The authors also show that government policy is unclear. Republic Act
8042, the Migrant Workers and Overseas Filipinos Act of 1995, says that
the State “does not promote overseas employment” as a way to grow the
economy (Section 2c). Yet the same law says that the deployment of
overseas Filipino workers “shall be encouraged” (Section 2i).

The **knowledge gap** is that the causes of emigration from the
Philippines are “not well established.” Policymakers need evidence on
which push factors matter most. The **research question** is: How do
economic, demographic and political factors affect emigration from the
Philippines?

> **Critical comment:** The problem is clear and important. However, the
> authors do not review earlier studies on Philippine emigration in
> detail. As a result, the gap is stated more than it is shown.

# 2. Theoretical Framework

The authors admit that no single theory explains emigration. They
combine ideas from four theories:

- **Ravenstein (1885) and Todaro (1969):** people migrate when they
  expect a better life abroad.

- **Human capital theory (Hicks, 1939; Sjaastad, 1962):** migration is
  an investment, like going to school. More educated people are expected
  to migrate more.

- **The Roy effect (Borjas, 1987):** income inequality decides which
  skill groups leave.

- **The gravity model (Greenwood, 1975; Adams & Page, 2003):** migration
  depends on income, population and the cost of migration.

From these ideas, the authors build one equation. The migration share
depends on nine explanatory variables: cost of migration, adult
literacy, income inequality, income inequality squared, political
instability, inflation, population density, unemployment and per capita
income.

> **Critical comment:** The framework is a mix of theories, not one
> clear model. The theories are used mainly to predict whether each
> coefficient should be positive or negative. Also, the gravity model
> normally compares two places: the home country and the destination
> country. This study uses only push factors from the Philippines. Pull
> factors from destination countries are left out.

# 3. Data

The study uses yearly national data from 1975 to 2005. This gives only
31 observations, one per year. All the data are secondary data, which
means other agencies collected them. Table 2 shows each variable, how it
is measured, where it comes from, and the sign the authors expected for
its coefficient.

| **Variable**                          | **Measure / proxy**                                                    | **Source**             | **Expected sign** |
|---------------------------------------|------------------------------------------------------------------------|------------------------|-------------------|
| Migration share                       | Migrants (temporary and permanent) ÷ population                        | CFO; NSCB              | (explained)       |
| Cost of migration                     | Average one-way airfare from Manila to the top 24 destinations (proxy) | Authors’ estimate      | Negative          |
| Adult literacy                        | Adult literacy rate (proxy for education)                              | BSP; NSCB              | Positive          |
| Income inequality, income inequality² | Gini coefficient and its square (Roy effect)                           | Not stated             | Unclear           |
| Political instability                 | Number of leadership changes, coups and uprisings                      | Gastil (1987) approach | Negative          |
| Inflation                             | Inflation rate (consumer prices)                                       | IMF; BSP; NSCB         | Negative          |
| Population density                    | People per square kilometre                                            | NSCB                   | Positive          |
| Unemployment                          | Unemployment rate                                                      | IMF; BSP; NSCB         | Positive          |
| Per capita income                     | Real GDP per person                                                    | IMF; BSP; NSCB         | Negative          |

*Table 2. Variables and data sources. CFO = Commission on Filipinos
Overseas; NSCB = National Statistical Coordination Board; BSP = Bangko
Sentral ng Pilipinas; IMF = International Monetary Fund.*

Two measures are proxies. Airfare stands in for the cost of migration,
and adult literacy stands in for education, because data on schooling
levels were not available for the whole period.

> **Critical comment:** The paper does not say where the income
> inequality data came from. This matters because the Philippines
> measures the Gini coefficient only every few years, so the yearly
> values were probably estimated, but this is not explained. The
> migration share also mixes temporary workers and permanent emigrants,
> who may leave for different reasons.

# 4. Methodology

The study uses a quantitative, time-series approach. It analyses one
country using national data. The methodology has five steps:

1.  **Unit root tests.** The Augmented Dickey–Fuller (ADF) and
    Phillips–Perron (P–P) tests check whether each time series is
    stationary. Most variables are not stationary at first, but they
    become stationary after taking first differences.

2.  **Cointegration tests.** The Engle–Granger test, the Johansen test
    and the Pesaran bounds test all show cointegration. This means the
    variables move together in the long run.

3.  **Choosing the model.** The authors use a general-to-specific
    approach (Hendry & Ericsson, 1991). They start with a large model
    and drop the terms that are not statistically significant, one at a
    time.

4.  **Estimation.** The final ECM is estimated using ordinary least
    squares (OLS) in the EViews 6.0 software.

5.  **Diagnostic tests.** The authors check the model for common
    problems: errors that are linked over time (Breusch–Godfrey test), a
    wrong model form (Ramsey RESET test), errors that are not normally
    distributed (Jarque–Bera test), errors whose spread changes over
    time (ARCH test), and coefficients that are not stable (CUSUM test).
    The model passes all of these tests.

> **Critical comment:** The steps are standard and carefully done.
> However, there are three problems. First, the Johansen test finds five
> to eight long-run relationships, but the ECM keeps only one ECT.
> Second, the P–P test shows that per capita income is still not
> stationary after first differences (t = −2.123), and the authors do
> not discuss this. Third, 31 observations is a small sample for an ECM
> with ten explanatory terms (nine variables plus the ECT). With a small
> sample, the tests have low power, which means they may miss real
> effects.

# 5. Key Findings

## How well the model fits

- **Adjusted R² = 0.63.** The model explains 63% of the changes in the
  migration share.

- **ECT = −0.776.** About 78% of any gap from the long-run relationship
  closes within one year.

- **F-statistic = 5.848 (p = 0.000).** The explanatory variables matter
  when taken together.

## Four statistically significant push factors

| **Explanatory variable** | **Coefficient** | **t-statistic** | **What it means**                                                                                                  |
|--------------------------|-----------------|-----------------|--------------------------------------------------------------------------------------------------------------------|
| Unemployment             | +0.236          | 4.629           | Higher unemployment raises emigration. Emigration acts as a “safety valve” when there are not enough jobs.         |
| Adult literacy           | −0.659          | −5.225          | Higher adult literacy lowers emigration. This is the opposite of human capital theory.                             |
| Political instability    | −0.482          | −3.444          | More political instability lowers emigration. The migration share fell in unstable years (1983, 1986, 2001, 2005). |
| Population density       | −0.254          | −2.756          | Higher population density lowers emigration. This is the opposite of what was expected.                            |

*Table 3. Statistically significant explanatory variables (from Table 3
of the article).*

The authors explain the adult literacy result by saying that most
Filipino migrants do low-skilled jobs abroad, so more education keeps
people at home. They cannot fully explain the population density result.
One possible reason they give is that a larger population creates more
demand for local goods, which creates more jobs at home.

## Results that are not statistically significant

- **Cost of migration, per capita income and inflation** have the
  expected negative sign, but their effects could be due to chance.

- **Income inequality and income inequality squared** are not
  statistically significant. This means the Roy effect does not hold for
  the Philippines.

## The authors’ conclusions

The main push factors are unemployment, adult literacy, political
instability and population density. The authors recommend that the
government (1) collect and track migration data better, (2) sign
agreements with destination countries to protect overseas Filipino
workers, and (3) build a home economy with enough jobs, so the country
relies less on emigration.

# 6. Critical Assessment

## Strengths

- The research question is important for a country that sends many
  workers abroad.

- The steps are careful: unit root tests, then cointegration tests, then
  the ECM.

- All diagnostic tests are reported, and the model passes them.

- The paper explains the policy background well, including the unclear
  wording of RA 8042.

## Weaknesses

- **Small sample.** 31 yearly observations is small for ten explanatory
  terms, so the results may not be reliable.

- **Weak proxies.** Airfare is only the minimum cost of migration. Adult
  literacy in the Philippines was already very high for most of the
  period, so it changes little and is a weak proxy for education.

- **Push factors only.** The study ignores pull factors, such as job
  demand in the Middle East, which drove much of Filipino labour
  emigration.

- **A conflicting explanation.** The authors say adult literacy lowers
  emigration because migrants are low-skilled. But the paper itself
  cites Alburo and Abella (2002), who found that more Filipino
  professionals went abroad than were added to the workforce at home.

- **Unclear test results.** Per capita income is not stationary in the
  P–P test, and there are no tests for structural breaks (sudden
  changes), such as the 1986 EDSA Revolution or the 1997 Asian financial
  crisis.

# 7. Areas for Further Research

## Limitations the authors identify

- Migration data are hard to collect and compile.

- Airfare shows only the minimum cost of migration.

- The population density result is hard to explain and needs more
  research.

- The data cannot prove the political instability story.

## Future research opportunities

The authors call for more research on the population density result and
for better migration data. Building on the weaknesses above, I suggest
four more directions:

1.  **Split the data.** Study temporary and permanent migrants
    separately, and group migrants by skill level.

2.  **Add pull factors.** Include wages and job demand in destination
    countries.

3.  **Update the data.** Extend the data past 2005 and test for
    structural breaks, such as the 1997 Asian financial crisis, the 2008
    global financial crisis and COVID-19.

4.  **Use household data.** Use survey data on individual migrants to
    test human capital theory directly.

# Conclusion

Agbola and Acupan (2010) show that push factors at home shape Filipino
emigration. Unemployment raises emigration, while adult literacy,
political instability and population density lower it. The study gives
useful early evidence and a clear policy message: build a home economy
with enough jobs. However, the small sample, the weak proxies and the
missing pull factors mean the results should be read with care. They are
a starting point for further research, not a final answer.

# Reference

Agbola, F. W., & Acupan, A. B. (2010). An empirical analysis of
international labour migration in the Philippines. *Economic Systems,
34*, 386–396. https://doi.org/10.1016/j.ecosys.2010.03.002

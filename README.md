# Global Terrorism Report — Data Analysis Dashboard

**Tools:** Power BI, DAX  
**Domain:** Security Analytics | Geopolitical Data | Trend Analysis  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

> **Note:** This project analyzes publicly available terrorism data for analytical and awareness purposes only. All figures represent recorded incidents from official databases and are intended to support data-driven understanding of global security trends.

---

## Project Overview

This project analyzes global terrorism data spanning from 1970 to recent years, covering 202,000+ recorded attacks across all world regions. The dashboard surfaces patterns in attack frequency, casualty rates, weapon types, target categories, and the most active terrorist organizations — enabling data-driven understanding of how terrorism has evolved over decades.

---

## Dashboard Preview

<img width="978" height="554" alt="image" src="https://github.com/user-attachments/assets/f782b2aa-8a07-4e8c-af07-6c2108398fef" />


---

## Key Metrics

| Metric | Value |
|---|---|
| Total Attacks Recorded | 202,000 |
| Overall Success Rate | 89% |
| Total Killed | 483,000 |
| Total Casualties | 1,000,000 |

---

## Dashboard Features

- **Most Common Targets** — ranked bar chart of target categories by attack frequency
- **Most Active Terrorist Groups** — top organizations by total attacks
- **Most Attacks by Country** — countries ranked by total incident count
- **Most Common Attack Types** — method of attack frequency breakdown
- **Casualties by Year** — trend line of annual casualty counts from 1950 to present
- **Weapon by Region matrix** — cross-tab of weapon types used across geographic regions
- **Terrorist Attacks Across Regions over Years** — multi-line trend chart showing regional attack patterns from 1970 onwards

---

## Key Findings

**1. Private citizens are the most targeted group (50K incidents)**
Civilians and private property account for the largest share of attacks, followed by Military (32K), Police (27K), Government (23K), and Business (22K). This pattern reflects terrorism's primary goal of creating public fear rather than direct military confrontation.

**2. 89% of attacks succeed — security response is chronically reactive**
The extremely high success rate across 202K attacks indicates that preventive measures have historically struggled to intercept planned attacks before execution.

**3. Unknown groups account for the most attacks (89K)**
The majority of recorded attacks have no confirmed attribution — highlighting the significant challenge of intelligence gathering and group identification in counterterrorism operations.

**4. Taliban (10K) and Islamic State (7K) are the most identified active groups**
Among named organizations, Taliban and ISIS/ISIL dominate recorded incident counts, concentrated heavily in South Asia and the Middle East respectively.

**5. Iraq leads all countries with 27K attacks**
Iraq, Afghanistan (16K), Pakistan (15K), and India (14K) form the top four most affected nations — all sharing characteristics of ongoing or recent internal conflict alongside external terrorist activity.

**6. Hostage taking / kidnapping is the most common attack type (13K)**
Contrary to media perception, explosive attacks are not the most frequent method. Kidnapping and hostage-taking dominate, particularly in regions where ransom financing supports terrorist operations.

**7. Casualties spike sharply post-2000, peaking around 2014**
The casualties by year trend shows relatively flat activity pre-2000, with a dramatic rise from 2003 onwards coinciding with the Iraq War and the rise of ISIS, peaking at 94K casualties in a single year around 2014.

**8. Explosives are the dominant weapon across all regions**
The weapon-by-region matrix shows explosives used at 30,100+ incidents in the Middle East & North Africa alone — far exceeding all other weapon categories in every region.

---

## Regional Attack Trends

| Region | Pattern |
|---|---|
| Middle East & North Africa | Dramatic spike post-2003, sustained high activity |
| South Asia | Steady increase from 1990s, peak around 2010-2015 |
| Central America & Caribbean | High activity in 1980s, sharp decline post-Cold War |
| Western Europe | Consistent low-level activity with periodic spikes |
| Sub-Saharan Africa | Rising trend from 2010 onwards |
| North America | Low frequency with isolated high-casualty events |

---

## Technical Highlights

- Time-series trend chart spanning 70+ years of data
- Regional cross-filtering enabling continent-level analysis
- Weapon type matrix combining geographic and categorical dimensions
- DAX measures for success rate calculation and casualty aggregations
- Multi-series line chart handling 10 simultaneous regional trend lines

---

## Data Source

Global Terrorism Database (GTD) — National Consortium for the Study of Terrorism and Responses to Terrorism (START), University of Maryland.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*

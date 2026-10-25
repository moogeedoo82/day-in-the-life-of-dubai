# A Day in the Life of Dubai

An interactive 24-hour visualization of life in Dubai.

This project uses **official Dubai/UAE statistics as calibration inputs** and combines them with **clearly documented modeling assumptions** to simulate how 1,000 representative residents move through daily activities.

> **Important:** This is an evidence-calibrated statistical model, **not a direct Dubai time-use survey**. The minute-by-minute activity percentages and transitions are modeled outputs.

## Live visualization

**[Open the interactive visualization](https://astonishing-cascaron-2540b3.netlify.app/)**

The interactive chart is hosted on Netlify. This repository contains the project documentation and methodology.
## What the visualization shows

Each moving dot represents approximately **4,471 Dubai residents**, using a resident population scale of approximately **4.471 million (Q3 2025)**.

The model includes 17 activity categories:

1. Work
2. Eating & Drinking
3. Traveling
4. Education
5. Sleeping
6. Leisure
7. Shopping
8. Sports
9. Religion
10. Personal Care
11. Household Care
12. Non-Household Care
13. Professional Care Services
14. Volunteering
15. Phone Calls
16. Housework
17. Miscellaneous

The interface includes:

- Animated movement between activity clusters
- Slow / Medium / Fast playback
- Time-of-day slider
- Representative weekday / weekend scenario
- Evidence and methodology section
- Official-data versus model-assumption labeling
- Vibrant category colors with subtle particle glow

## Data foundation

The visualization is calibrated using official or authoritative Dubai/UAE indicators where available, including:

- Dubai resident population and age structure
- Peak active population
- Labour-force participation
- Private-school enrolment
- Private higher-education enrolment
- Public transport, shared mobility and taxi ridership
- UAE working-hours framework
- Physical-activity indicators
- Dubai prayer-time timing

### Key calibration figures used

- Resident population scale: **4.471 million** (Q3 2025)
- Peak active population: **6.217 million** (Q3 2025)
- Age 25–44 share: **56.72%** (end-2024)
- Private-school students: **387,441** (2024–25)
- Private higher-education students: **42,026** (2024–25)
- RTA public transport/shared mobility/taxi riders: **747.1 million** (2024)
- Dubai Labour Force Survey refined economic participation rate used for calibration: **82.8%** (2019)
- DHA physical-activity reference: approximately **20% of adults aged 18+** had sufficient physical activity in the referenced 2019 indicator

## What is modeled

A public Dubai minute-by-minute time-diary microdataset was not identified for this project.

Therefore the following elements are **modeled assumptions**, not direct measured Dubai time-use statistics:

- Exact sleep and wake times
- Work and school start-time distributions
- Commute duration distributions
- Meal timing and duration
- Shopping participation
- Household and non-household care
- Phone calls
- Volunteering
- Professional care services
- Religious participation rates
- Weekend activity sequencing
- Minute-by-minute transitions between activities

The project deliberately exposes this distinction so that the model can be refined when better Dubai time-use microdata becomes available.

## Primary sources

- [Dubai Data & Statistics Establishment — Dubai in Figures](https://www.dsc.gov.ae/ar-ae/Pages/dubainfigure-details.aspx)
- [Dubai Population Bulletin 2024](https://www.dsc.gov.ae/Publication/Population%20Bulletin%20Emirate%20of%20Dubai%20-%202024.pdf)
- [Dubai Labour Force Survey results](https://www.dsc.gov.ae/en-us/DSC-News/Pages/Dubai-Unemployment-Rate-is-0.5-Percentage-Point.aspx/1000)
- [KHDA — Dubai private-school landscape](https://web.khda.gov.ae/en/About-Us/News/2025/Dubais-private-school-sector-records-6-enrolment)
- [KHDA — Dubai private higher education](https://web.khda.gov.ae/en/About-Us/News/2025/Dubais-private-higher-education-sector-continues)
- [RTA — 2024 public transport/shared mobility/taxi ridership](https://rta.ae/wps/portal/rta/ae/home/news-and-media/all-news/NewsDetails/747-million-riders-used-public-transport-shared-mobility-and-taxis-in-2024)
- [UAE Government — Working hours](https://u.ae/en/information-and-services/jobs/employment-in-the-private-sector/working-hours)
- [Dubai Health Authority — Physical Activity Guideline 2026](https://dha.gov.ae/uploads/042026/Physical%20Activity%20Guideline2026429979.pdf)
- [IACAD — Dulook DXB prayer-time service](https://ipt.iacad.gov.ae/)

## Technology

This project is deliberately lightweight:

- HTML5
- CSS
- Vanilla JavaScript
- HTML5 Canvas

No build process or external JavaScript libraries are required.


## Interpretation

The animation should be read as:

> **A statistical model based on real Dubai/UAE data — not direct measured time-use data.**

It is intended for data visualization, analytical storytelling, methodological exploration, and portfolio demonstration.

## Author

**Mohamed Abdelmaguid**  
Data Analytics · Business Intelligence · Automation · Data Visualization

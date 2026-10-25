# A Day in the Life of Dubai

An interactive 24-hour visualization of life in Dubai.

This project uses **official Dubai/UAE statistics as calibration inputs** and combines them with **clearly documented modeling assumptions** to simulate how 1,000 representative residents move through daily activities.

> **Important:** This is an evidence-calibrated statistical model, **not a direct Dubai time-use survey**. The minute-by-minute activity percentages and transitions are modeled outputs.

## Live visualization

**[Open the interactive visualization](https://day-in-the-life-of-dubai.netlify.app/)**

The interactive chart is hosted on Netlify. This repository contains the project documentation and methodology.
## What the visualization shows

The visualization presents a modeled 24-hour day in Dubai across 17 activity categories:

- Work
- Eating & Drinking
- Traveling
- Education
- Sleeping
- Leisure
- Shopping
- Sports
- Religion
- Personal Care
- Household Care
- Non-Household Care
- Professional Care Services
- Volunteering
- Phone Calls
- Housework
- Miscellaneous

The interface includes animated movement between activity clusters, playback-speed controls, a time-of-day slider, weekday/weekend scenarios, a hands-only analog clock synchronized with the simulated time, a compact About this chart explanation, and clear labeling of official-data inputs versus model assumptions.

## Data foundation

The visualization is calibrated using official or authoritative Dubai/UAE indicators where available, including population structure, labour-force indicators, education, mobility, working-hours guidance, physical activity, and prayer-time timing.

No source datasets or raw data files are stored in this repository.

## What is modeled

A public Dubai minute-by-minute time-diary microdataset was not identified for this project.

The minute-by-minute activity sequence is therefore a statistical model using documented assumptions for timing and participation patterns. These assumptions are shown in the live visualization and are not presented as direct measured Dubai time-use statistics.

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


## Copyright

© 2026 Mohamed Abdelmaguid. All rights reserved.

This repository and the associated visualization are provided for viewing and portfolio demonstration only. No permission is granted to copy, reproduce, redistribute, republish, modify, or create derivative works from the visualization, design, methodology, or implementation without the author's prior written permission.

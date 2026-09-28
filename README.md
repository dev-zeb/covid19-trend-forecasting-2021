# COVID-19 Epidemic Trend Forecasting (2021)

This repository documents a five-person final-year design project completed at United International University in 2021. We explored COVID-19 trends for Bangladesh and worldwide data, compared several forecasting methods, and evaluated a weighted ensemble. It is an archive of the academic work, not a current forecasting service.

## Project at a glance

- **Data:** Historical COVID-19 case records described in the project report, principally sourced from the Johns Hopkins University CSSE data repository. The final report describes records from January 22, 2020 through February 27, 2021.
- **Analysis:** Data preparation and exploratory visualizations of confirmed, recovered, death, active, and closed cases.
- **Methods:** Holt's linear trend, Holt-Winters exponential smoothing, polynomial regression, support vector regression, and a weighted-average ensemble of their predictions.
- **Evaluation reported in 2021:** RMSE, MAPE, and R-squared for Bangladesh and worldwide results. See the report for individual targets, tables, and experimental context.

## Original project materials

- [Final project report (PDF)](report/final-report.pdf)
- [Defence presentation (PDF)](slides/defence-slides.pdf)

The figures below are selected historical visualizations from the project. They describe the dataset available to the team at the time; they do not describe current COVID-19 conditions.

![Historical active and closed case series worldwide](figures/active-vs-closed.png)

*Figure: Worldwide active and closed case series as presented in the 2021 project.*

![Historical case distributions for ten countries](figures/top-ten-countries.png)

*Figure: The report's distributions of confirmed, death, and recovered cases among the countries displayed in each chart.*

## Scope and limitations

This is a **team project**, and the report and slides are the sources for the methodology and historical results. The original implementation code and training artifacts are not available in this repository, so the published figures and metrics have not been independently reproduced here. The report states that the team did not use a separate test dataset and instead split the data into training and validation sets. It also notes limits in compute, time for tuning, and available features. Treat the reported metrics as historical course-project results, not as validated performance on new outbreaks or as medical or public-health guidance.

This repository does not claim that the project was published as a research paper. For related research, see the references in the final report; the referenced papers are the work of their respective authors.

## Credits

Completed by a five-person final-year design-project team at United International University under the academic supervision documented in the report. Individual contributions should be added here only after they are confirmed with the team.
